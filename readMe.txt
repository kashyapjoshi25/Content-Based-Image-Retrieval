-Language Used
 Python 3

-Editor Used
 Google Colab

 
-To Create the Pre-Processed File, Follow the Below Steps:-
  1) Open Google Colab or any other notebook( Recommended: Google Colab)

  2) Upload the dataset file in google drive(While uploading the file on google drive, directly upload the file in google drive without changing the name and do not put the file in any folder). 
DataSet links:
DataSet 1:https://drive.google.com/drive/folders/1rYV3_ueTcvXgXT7imKZzqYzKcsZqEHHm?usp=share_link
DataSet 2:https://drive.google.com/drive/folders/1bfUqzHvzU9anWAcmAF7siAfVXvzJ7hgQ?usp=share_link

3) To insert a Query Image upload it on drive and pass the name "img = Image.open('/content/George_W_Bush_0374.jpg')
imgGray = cv2.imread('/content/George_W_Bush_0374.jpg')" in the code.

  4)After uploading, open the ipynb file in the notebook and fire the run-all command(For Google Colab command is "Ctrl+F9" for run all) 

 

- Output

After Completion of running, you will be able to see the below results.
1)K Similar images of Query Image(K=5 , can change the number of k by changig the parameter k in define knn method)
2)Predicted Label using knn algorithm
3)Testing accuracy of svm model
4)Predicted Label using svm algorithm





