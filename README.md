# learningWritedown
#在jupyter中修改默认浏览器操作，改变文件路径为:
4、import webbrowser
webbrowser.register("chrome",None,webbrowser.GenericBrowser(u"C:\\ProgramFiles(x86)\\Google\\Chrome\\Application\\chrome.exe"))

c.NotebookApp.browser = 'chrome'(路径为\，而不是/)
