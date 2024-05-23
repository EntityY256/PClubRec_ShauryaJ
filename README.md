# PClubRec_ShauryaJ

Hello. This is my submission for The NLP recruitment task for PClub.
I'll explain the logics right away.
I had trouble in hosting 2 gradio models from the same google colab notebook, so I made 2 different notebooks for the same. Both have nearly identical code, but while the 1st model gives 5 relevant paragraphs wrt the given line, the 2nd model gives few sentences which best answers the query.
Link to the gradio for 1st notebook : https://843ee4d4a126e9e857.gradio.live
Link to the gradio for 1st notebook : https://5a177f5ec41795dc01.gradio.live
There are 2 parts in both notebooks. The 1st part is used to extract possible data from given datasheets.
The 2nd part (labelled modelling) can be run by running each code snippets sequentially. Just upload all these model and csv files before U run them

Pytorch can be used to convert sentences to vecotrs, which can then be compared using cosine similarity formula. This is the main logic by which we get our comparisions of texts with input query.
We used pytorch tensors and converted all sentences to tensors, which then gets converted back to text after comparision,
![Screenshot (44)](https://github.com/EntityY256/PClubRec_ShauryaJ/assets/143442236/2fb77788-9741-4b3a-bf8e-53e0d0892969)
