# geeknote.md

#
# Login failure: fix oauth.py

See: github.com/VitaliyRodnenko/geeknote/pull/290/files

		193	        hpts = re.search('.*\("hpts"\)\.value.*?"(.*?)"', response.data)
		194	        hptsh = re.search('.*\("hptsh"\)\.value.*?"(.*?)"', response.data)
