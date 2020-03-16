# cheatsheet
#authentication
https://laravel.com/docs/6.x/authentication
#routy
https://laravel.com/docs/5.7/controllers#resource-controllers

#eventbus
```
import { EventBus } from '@/event-bus.js';
//emitowanie
EventBus.$emit('nav', '');

//event-bus.js
import Vue from 'vue';
export const EventBus = new Vue();

//odbieranie
EventBus.$on('nav', payload => {
    this.showIn();
    });
```   

#slice
```
  arr = ['a','b','c','d','e','f','g'];
  console.log(arr.slice(1)); -> ['b','c','d','e','f','g'];
  console.log(arr.slice(0,1)); -> ['a'];
  console.log(arr.slice(0,-2))->["a", "b", "c", "d", "e"];
  console.log(arr.slice(arr.length-2))->["f", "g"] ;
```  
