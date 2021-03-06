# Credits, Notes, and Reference

## Professor Rossetti's Previous Courses

  + [Internet Programming](https://github.com/prof-rossetti/southernct-csc-443-01-201701)
  + [Database Design and Applications](https://github.com/prof-rossetti/gwu-istm-4121-10-201509)
  + [Management Info Systems](https://github.com/prof-rossetti/gwu-badm-2301-11-201509)

## Related NYU Courses and Resources

  + [NYU Data-driven Decision-making](http://www.d3mprof.com/)
  + [NYU Data Bootcamp](https://github.com/NYUDataBootcamp)
  + [NYU Principles of Urban Informatics](https://github.com/fedhere/PUI2016_fb55)

## NYU Services and Resources

  + [NYU Software](http://www.nyu.edu/life/information-technology/getting-started/software.html)
  + [NYU Co-Op Laptop Loaning](http://www.nyu.edu/life/information-technology/locations-and-facilities/student-technology-centers/laguardia-co-op.html#Laptop)
  + [NYU Lynda](https://www.nyu.edu/lynda)
  + [NYU Classroom AV Services](https://nyu.service-now.com/servicelink/kb_search.do?id=KB0013493)
  + [NYU Faculty](https://www.nyu.edu/faculty.html)
  + [Adding TA Permissions in NYU Classes](https://nyu.service-now.com/servicelink/kb_search.do?id=KB0010347)
  + [NYU Classroom Reservations](https://virtualems.stern.nyu.edu/BrowseReservations.aspx)
  + [NYU Schools and Colleges](https://www.nyu.edu/academics/schools-and-colleges.html)

## Configuring Mediasite in NYU Classes

> Typically, once you request recordings and autoposting, the only other thing you need to do is set the Mediasite tab on your NYU Classes course site to visible via settings > tool order > mediasite. Recordings will show up in this tab a few weeks after you enter the request via virtual EMS.

## Screencasting

  + [Converting QuickTime screen recordings to GIF format](https://gist.github.com/dergachev/4627207)): `ffmpeg -i ~/Dropbox/Screenshares/YOUR_SCREENCAST.mov -pix_fmt rgb24 -r 10 -f gif - | gifsicle --optimize=3 --delay=3 > admin/YOUR_SCREENCAST.gif`
  + [Hiding all Folders on the Desktop](http://www.cultofmac.com/272595/quickly-hide-icons-desktop-os-x-tips/): `defaults write com.apple.finder CreateDesktop false && killall Finder`
  + Recording a screencast with audio (ALMOST, BUT NOT FULLY WORKING):
    + http://apple.stackexchange.com/a/213305/94120
    + https://www.cnet.com/how-to/record-your-computers-screen-with-audio-on-a-mac/
    + https://github.com/mattingalls/Soundflower/releases/tag/2.0b2
