# Reactjs
My first respository on github
Implement for hooks
--------------------
      App.js
--------------------
import React,{useState} from 'react'
//import Header from './Header'

function App(){
	var style={
		background:"green"
	}
	var changeBackground=(e)=>{
		e.target.style.background="green";
	}
	var changeBackground=(e)=>{
	e.target.setAttribute('class','changeBackground')
	}
	const [data,setData]=useState({"name":"Likhitha","role":"Software Engenieer"})
	return (
		<>
			<h2 onMouseOver={(e)=>{changeBackground(e)}}> {data.name} is working as {data.role}. </h2>
		</>
	)
}



import React,{useState} from 'react';
import './App.css';
import Header from './Header';

function App(){
  var data=["Durga","Raja","Likhitha","Upendra","Vamsi"]
  var rolesData=["S/w engineer","Testing engineer","Web developer","App developer",Ios developer"]
  return(
    <>
      <h2> Sample Data </h2>
      {(()=>{
      	for(var i in data){
      	  // <Header name={data[i]} role={rolesData[i]}/>
	   console.log(data[i])
      
      })()}
     
    </>
  )
}
export default App;



     Header.js
let Header=(props)=>{
  return {
  	<header>
    		<h2> 

















