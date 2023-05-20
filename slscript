#Requires AutoHotkey v2.0
scroll_on := 0

ScrollLock::
{
	global scroll_on
	scroll_on := !scroll_on
	return
}
Down::
{
	global scroll_on
	If scroll_on = 0
		Send "{Down}"
	Else
		Send "{WheelDown 1}"
	return
}
Up::
{
	global scroll_on
	If scroll_on = 0
		Send "{Up}"
	Else
		Send "{WheelUp 1}"
	return
}
