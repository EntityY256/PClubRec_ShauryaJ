# PClubRec_ShauryaJ

Hello. This is my submission for The NLP recruitment task for PClub.
I'll explain the logics right away.
I had trouble in hosting 2 gradio models from the same google colab notebook, so I made 2 different notebooks for the same. Both have nearly identical code, but while the 1st model gives 5 relevant paragraphs wrt the given line, the 2nd model gives few sentences which best answers the query.
Link to the gradio for 1st notebook : https://843ee4d4a126e9e857.gradio.live
There are 2 parts in both notebooks. The 1st part is used to extract possible
Pytorch can be used to convert sentences to vecotrs, which can then be compared using cosine similarity formula. This is the main logic by which we get our comparisions of texts with input query.
