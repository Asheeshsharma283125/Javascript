# Javascript
/* type of Console
1.Console.time(); // to calcute the time 
2.Console.log("To show something on Desktop");
3.Console.log({marks:12,Name:'Asheesh','Sec':H}); //left hand side is an object
4.Console.table({marks:13,Name:'Asheesh'}); //it show you in table form
5.Console.warn('this to show you Warning on console');
6.Console.clear();
7.Cosole.timeEnd();
8.Console.assert(age>120,"this is Wrong Entry");
*/

//keywords let,var,const

//Variable declaration Conditions
//1.Cannot start with Number
//2.Start with letters,_,$
//3.Case sensitive

var a = 2;
Console.log(a);  //it has same variable name but its show 2
{
let a = 45;
Console.log(a); //Output=45
}
const b = "asheesh";
b = "ashish";  //Output= Error
const c = [12,23,4,65];
c.push(6);  //Output= [12,23,4,65,6]

//Naming Varieties
//1.camelCase (stackByArray)
//2.Kabab-Case (Asheesh-ashish)
//3.Snake_Case (Asheesh_ashish)
//4.PascalCase (StackByArray)

//Primitive Data Types  Number,String,undefined,null,Boolean
//Reference Data Types(derived) Array,Object Laternals,Functions,Dates(let date = new Date())

//Type Conversion
let a = String(23);
Console.log(typeof a); //String
let a = Number("Asheesh");
Console.log(a ,typeof a); //Nan Number
let a = Number(true);
console.log(a) // 1 type-Number
let a = Boolean("ashu") //true
let a = String(new Date()); //String 
let a = parseInt(39.4567); //39
let a = Numnber(39.5677);  //39.5677
a.toFixed(2); //39.56
let a = parseFloat(39.56);


//Coercion
let a = "asheesh"
let b = 23;
let c = a + b; //asheesh23 (When two different type concat)


