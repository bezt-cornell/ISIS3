APPNAME = mdis2isis

#NOPREFERENCES=
include $(ISISROOT)/make/isismake.tsts

commands:
	$(APPNAME) from=$(INPUT)/EN0215850728M.IMG \
	  to=$(OUTPUT)/EN0215850728M.cub > /dev/null
	catlab from=$(OUTPUT)/EN0215850728M.cub \
	  to=$(OUTPUT)/EN0215850728M.pvl> /dev/null
