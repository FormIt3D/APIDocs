# APIDocs
WSM and FormIt API documentation

# Generating Documentation
Follow directions from https://git.autodesk.com/FormIt360/FormIt360/tree/master/Tools/Doxygen to install the necessary python requirements to run doxygen. (Note: The most recent doxygen version as of this writing used to generate docs was 1.9.8)

Run the following documentation sets:
```
python3 ./Generate_Doc.py -l WSM_API
python3 ./Generate_Doc.py -l FORMIT_API
python3 ./Generate_Doc.py -l JS_API
```

This will output documentation html files in `doc.generated.pass3\html` folder of these paths:

```
out.FORMIT_API
out.JS_API
out.WSM_API
```

Copy the contents of those folders to their respective directories in the `APIDocs` repository: (Note: Delete the contents of these folders before copying in new content)

```
FormItCPPAPI
FormItJSAPI
FormItWSMAPI
```

