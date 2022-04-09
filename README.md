# ui-demo-package-library

This is a demo library, it has two components. One is button component with two variants and other is card component with two variants.

## Button Variants 

![image](https://user-images.githubusercontent.com/87171452/162556401-9978c1d1-d748-49af-b48c-d74cdd049ffc.png) <br/>
![image](https://user-images.githubusercontent.com/87171452/162556421-67e2a236-41e2-44ac-9e2c-e16eef531c70.png)

## Card Variants 

![image](https://user-images.githubusercontent.com/87171452/162556493-ed1a9d73-67fa-419c-8e03-96d19a771439.png) <br />
![image](https://user-images.githubusercontent.com/87171452/162556500-14622a20-aa6e-4615-a766-1af8e7b81e9e.png)

You can import this library into your project using the command 
``` sh
npm i ui-demo-package-library
```

***
# Here is the demo for using this UI Library

Let's start by creating a fresh Vue project 
``` sh
vue create projectname
```

cd into the project directory 

``` sh 
cd projectname 
``` 
In this project install this UI Library 
``` sh
npm i ui-demo-package-library
```
![image](https://user-images.githubusercontent.com/87171452/162560215-070b2b82-0d25-425d-859b-8a630c7e9512.png)

Now you can directly import the components from library using 
``` sh 
import component_name from 'ui-demo-package-library/src/lib-components/component_name.vue
```

Replace code of src/App.vue by 
``` sh 
<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <VueButton class="outlined" text="Click ME"/>
  </div>
</template>

<script>

import VueButton from 'ui-demo-package-library/src/lib-components/Vue-button.vue';

export default {
  name: 'App',
  components: {
    VueButton
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
```

Output would look something like this 
![image](https://user-images.githubusercontent.com/87171452/162560423-192b7a77-440a-4cee-aa47-48e1c44e1d12.png)

If you change class with background like this 
``` sh 
<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <VueButton class="background" text="Click ME"/>
  </div>
</template>

<script>

import VueButton from 'ui-demo-package-library/src/lib-components/Vue-button.vue';

export default {
  name: 'App',
  components: {
    VueButton
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
```

Output would look something like this 
![image](https://user-images.githubusercontent.com/87171452/162560489-e5d3decf-6110-4e2a-89ad-2f031ecc8e31.png)

similarly you can import card component as well 


