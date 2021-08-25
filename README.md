# Teona Porchkhidze :rocket::nerd_face:
##### Junior Frontend Developer

 
 <img src="https://i.ibb.co/f1kQP9S/Frame-1t-1.png" alt="img"> | Hello, I am Teona, 20 years old, Startuper and Junior Frontend Developer, who has passion to study programming and use it in a creative way...
 ------------ | -------------
## my goals in 2021-2022 🔥🔥🔥
* Teona as a Full Stack Developer :computer:	
* Having a successful startup - <a href="https://www.facebook.com/300tsavleblo">300წავლებლო :yellow_circle: 300tsavleblo </a> (it's educational startup) :raised_hands:
* Winning Grace Hopper award :trophy:

### Winner of BTU Startup demo day 🏆

#### Contact me :handshake:	

* <a href="https://www.facebook.com/teona.porchkhidze.7545/">Facebook</a>
* <a href="https://www.linkedin.com/in/teona-porchkhidze-b757b81b3/">LinkedIn</a>


#### Skills :dart:

<div align="center">
<img src="https://profilinator.rishav.dev/skills-assets/javascript-original.svg" alt="JavaScript" height="45" />
<img src="https://profilinator.rishav.dev/skills-assets/typescript-original.svg" alt="TypeScript" height="45" />
<img src="https://i.imgur.com/94n31ta.png?1" alt="HTML5" height="46" />
<img src="https://cdn.345tool.com/public/logos/css-formatter-logo.png" alt="CSS3" height="44" />
<img src="https://cdn.iconscout.com/icon/free/png-256/sass-2752078-2284895.png" alt="Sass" height="45" />
<img src="https://profilinator.rishav.dev/skills-assets/bootstrap-plain.svg" alt="Bootstrap" height="47" />
<img src="https://brandslogos.com/wp-content/uploads/images/large/react-logo.png" alt="React" height="46">
<img src="https://profilinator.rishav.dev/skills-assets/git-scm-icon.svg" alt="Git" height="48" />
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/1024px-Python-logo-notext.svg.png" alt="Python" height="45" />
<img src="https://profilinator.rishav.dev/skills-assets/linux-original.svg" alt="Linux" height="50" />
<img width=37px src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/22/Pandas_mark.svg/1200px-Pandas_mark.svg.png">
<img width=50px src="https://techscript24.com/wp-content/uploads/2020/10/86498201-a8bd8680-bd39-11ea-9d08-66b610a8dc01.png">

</div>

#### Code example :computer:	

```

class DB {
    constructor (){
       this.person = new Map();
       this.id = 0
    }
    
    create(person){
        if(typeof person !== 'object' || !person.name || !person.age || !person.salary || !person.country){
            throw new Error("blabla");
        }
        let user = this.person.set(this.id.toString(), person);
        let tempid = this.id
        this.id++;
        return tempid.toString();
        
    }
    read(id){
        if(typeof id !== 'string'){
            throw new Error ("id must be String");
        }
        else if (this.person.has(id) === false){
            return null;
        }
        else if(this.person.has(id)){
           return this.person.get(id);
      } 
    } 
    readAll(){
    if(arguments.length != 0) throw new Error('there shouldnt be any arguments')
    	let array = [];
      this.person.forEach((index)=>array.push(index));
      return array;
    }
    update(id,obj){
			if(!this.person.has(id) || typeof id != 'string' || Object.values(obj).length < 1)
      throw new Error('wrong id')
      this.person.set(id,{...this.person.get(id),...obj})
      return id;
    }
    delete(id){
    console.log(id, this.person.get(id))
    if(!this.person.has(id))throw new Error('that person doesnt exist')
    	return this.person.delete(id)
    }
}
const db = new DB();

const person1 = {
    name: 'Pitter', // required field with type string
    age: 21, // required field with type number
    country: 'ge', // required field with type string
    salary: 500 // required field with type number
};


let id1 = db.create(person1);
let id2 = db.create(person1);
let id3 = db.create(person1);
console.log(db.read(id1));
db.readAll();
db.update(id2, {age: 6});
db.update(id1, {age: 16, name: 'teo'});
db.delete(id3);
db.readAll();
```

#### Experience :briefcase:	

* <a href="https://github.com/Teona-tech/UnilabPythonDevelopment">Unilab Python Development Course (tasks)</a>
* <a href="https://github.com/Teona-tech/html-and-css-practices">Html and css practices</a>
* <a href="https://github.com/Teona-tech/personal-project-html-and-css">Personal Html and css project </a>
* <a href="https://github.com/Teona-tech/Personal-Project-SCSS">Personal-SCSS-Project</a>
* <a href="https://github.com/Teona-tech/js-practises">Javascript tasks</a>
* <a href="https://github.com/Teona-tech/JS-personal-project">Javascript personal project</a>
* <a href="https://github.com/Teona-tech/typescript-personal-project">Typescript pesronal project</a>


#### Education :student:	

where? | what?
 ------------ | -------------
<a href="http://www.geolab.edu.ge/"><img width=50px src="https://scontent.ftbs5-3.fna.fbcdn.net/v/t1.6435-9/145567197_2583997071890575_6494526563535501235_n.jpg?_nc_cat=109&ccb=1-5&_nc_sid=09cbfe&_nc_ohc=eIP5dqJ-xOUAX9I0RWS&_nc_ht=scontent.ftbs5-3.fna&oh=7f4027b0021e9fa6eb988a00b19c0e1a&oe=614C76BF"></a> | c#,Unity
<a href="https://unilab.iliauni.edu.ge/"><img width=50px src="https://scontent.ftbs5-2.fna.fbcdn.net/v/t1.6435-9/82785721_103798394508081_1561838589170417664_n.png?_nc_cat=110&ccb=1-5&_nc_sid=09cbfe&_nc_ohc=Sq34h1_3_g8AX8hJ0Ps&_nc_ht=scontent.ftbs5-2.fna&oh=7ec13e9731fbb516b6319548a672aebc&oe=614CE0C2"></a> | Python(Flask,NLTK)
<a href="https://btu.edu.ge/"><img width=50px src="https://scontent.ftbs5-2.fna.fbcdn.net/v/t1.6435-9/118974653_1185472291837040_8177821905411797845_n.png?_nc_cat=104&ccb=1-5&_nc_sid=09cbfe&_nc_ohc=ev5hrq64fMIAX_56nk9&_nc_ht=scontent.ftbs5-2.fna&oh=499df9ae592bcbe2bb41a84639555325&oe=614C3378"></a> | IT student - BTU
<a href="https://www.tbcitacademy.ge/"><img width=50px src="https://scontent.ftbs5-2.fna.fbcdn.net/v/t39.30808-6/219365098_10158163599556188_3659932507699574656_n.png?_nc_cat=1&ccb=1-5&_nc_sid=09cbfe&_nc_ohc=l6NMuEwyRh4AX9bNoki&_nc_ht=scontent.ftbs5-2.fna&oh=b18655e553e643dbbeb65b1d745ebc4d&oe=612AF296"></a> | Frontend Development
<a href="https://start.bitcamp.ge/"><img width=50px src="https://scontent.ftbs5-3.fna.fbcdn.net/v/t1.6435-9/122397052_388542505858688_891968229563768666_n.jpg?_nc_cat=109&ccb=1-5&_nc_sid=09cbfe&_nc_ohc=tY65Xwi7G6wAX-A5JMJ&_nc_ht=scontent.ftbs5-3.fna&oh=15b84176f09177bcaa4ea6bc426f8b96&oe=614A90CA"></a> | JS basics

#### English level
B2-C1


