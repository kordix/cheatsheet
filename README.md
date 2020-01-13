# cheatsheet
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
