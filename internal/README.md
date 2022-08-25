# Internal

The internal directory will contain various ancillary packages used by our API. It will
contain the code for interacting with our database, doing data validation, sending emails
and so on. Basically, any code which isn’t application-specific and can potentially be
reused will live in here. Our Go code under cmd/api or cmd/web will import the packages in the
internal directory (but never the other way around).
