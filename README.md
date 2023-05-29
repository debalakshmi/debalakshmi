<h2>Hi👋, I'm Deba! </h2>

<a href=#><img src="contributions.svg"></a>
<h3>Working as a Associate Analyst at <a href="https://www.ey.com">EY GDS</a><img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> 
</h3>

## Connect me on:

<a href="https://instagram.com/deba_lakshmi"><img src="https://cdn2.iconfinder.com/data/icons/social-media-2285/512/1_Instagram_colored_svg_1-512.png" width="26"> </a>
<a href="https://www.linkedin.com/in/debalakshmi"><img src="https://content.linkedin.com/content/dam/me/business/en-us/amp/brand-site/v2/bg/LI-Bug.svg.original.svg" width="30"> </a>


```python

class DataEngineer:
    def __init__(self):
        self.name = "Deba"
        self.role = "Associate analyst in EY GDS"
        self.location = "8.8932\xc2\xb0 N, 76.6141\xc2\xb0 E"
        self.knowledge_base = ["Data visualization", "SQL","ETL"]
        
    def say_hi(self):
        print( """Hello my friend, thanks for dropping by!
This is {name}, I live in {location}. I work as an {role}
I have wide interests, but most of them are {knowledge_base}.""".format(name=self.name,location=self.location,role=self.role,knowledge_base=self.knowledge_base)

me = DataEngineer()
me.say_hi()

```
<a href="https://pythontutor.com/visualize.html#code=class%20DataEngineer%3A%0A%20%20%20%20def%20__init__%28self%29%3A%0A%20%20%20%20%20%20%20%20self.name%20%3D%20%22Deba%22%0A%20%20%20%20%20%20%20%20self.role%20%3D%20%22Associate%20analyst%20in%20EY%20GDS%22%0A%20%20%20%20%20%20%20%20self.location%20%3D%20%228.8932%5Cxc2%5Cxb0%20N,%2076.6141%5Cxc2%5Cxb0%20E%22%0A%20%20%20%20%20%20%20%20self.knowledge_base%20%3D%20%5B%22Data%20visualization%22,%20%22SQL%22,%22ETL%22%5D%0A%20%20%20%20%20%20%20%20%0A%20%20%20%20def%20say_hi%28self%29%3A%0A%20%20%20%20%20%20%20%20print%28%22%22%22Hello%20my%20friend,%20thanks%20for%20dropping%20by!%0AThis%20is%20%7Bname%7D,%20I%20live%20in%20%7Blocation%7D.%20I%20work%20as%20an%20%7Brole%7D%0AI%20have%20wide%20interests,%20but%20most%20of%20them%20are%20%7Bknowledge_base%7D.%22%22%22.format%28name%3Dself.name,location%3Dself.location,role%3Dself.role,knowledge_base%3D%22,%20%22.join%28self.knowledge_base%5B1%3A%5D%29%29%29%0A%0Ame%20%3D%20DataEngineer%28%29%0Ame.say_hi%28%29&cumulative=false&curInstr=13&heapPrimitives=nevernest&mode=display&origin=opt-frontend.js&py=3&rawInputLstJSON=%5B%5D&textReferences=false">Click here, to run the code</a>
