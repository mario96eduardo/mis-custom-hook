# useForm  Hook

 Ejemplo de uso:

 ```

 const initialForm ={
     name:'',
     edad:0,
     email:''
 }
 const {values, handleInputChange,reset}=useForm(initialForm);

 ```
 useConter(10) // recibe un valor por defecto