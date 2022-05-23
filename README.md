1.from google.colab import files
2.uploaded=files.upload()
3.for fn in uploaded.keys():
       print ('Users uploaded file "{name}" with {length} bytes' . format (name=fn, length=Len(uploaded [fn])))
4.uploaded
