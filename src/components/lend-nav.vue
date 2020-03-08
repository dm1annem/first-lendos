<template>
    <div class="lend-nav">
        <ul>
          <li 
          v-for="item in menu"
          :key="item.name"
          >
            {{item.name}}
          </li>
        </ul>  
    </div>
</template>
<script>
export default{
    name: 'lend-nav',
    data() {
        return{
            menu: [
            {
                name: 'Главная',
                isActive: true
            },
            {
                name: 'Проекты',
                isActive: false
            },
            {
                name: 'Примеры работы',
                isActive: false
            },
            {
                name: 'Отзывы клиентов',
                isActive: false
            },
            {
                name: 'Контакты',
                isActive: false
            },
            
        ]

        }  
    },
    methods:{
        
    },
    created(){
        
    }
}
</script>
<style >
.lend-nav {
    background-color: #6e4444;
    
    
}
.lend-nav ul li {
    color: white;
}
</style>