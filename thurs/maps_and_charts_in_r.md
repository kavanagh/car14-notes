### Maps and charts in R

**Matt Waite: Github - mattwaite**

**All notes: <https://github.com/mattwaite/MapsAndChartsInR/blob/master/notes.md>**


* R: impenetrable, hates you, a lifetime commitment
* Fantastic tool but hard to learn
* Allows you to make statistical models, data visualisations, very powerful
* Integrated environment - no need to use a lot of different programmes. You do not need to leave the church of R!
* Easy to repeat things you have done
* Easy to iterate

* R doesn't care about spaces
* stat="bin" - default
* stat="identity" - identifying

* ggplot(data=enrollment, aes(x=Year, y=Students, fill=Year)) + geom_line() + ylim(0, *max(enrollment$Students))*
* In this - enrollment is the data source, then dollar sign, then Students = column name