<template>
    <section>
        <div class="footer container">
            <div class="footer_l">
                <div class="logo__header">
                    <img src="@/assets/images/Logo.jpg" alt="Logo" class="logo">
                     <a href="#" class="interno">Interno</a>
                </div> 
                <p class="slogan">It is a long established fact that a reader will be distracted lookings.</p>
                <div class="twitter">
                    <a href="#"><svg width="19" height="16" viewBox="0 0 19 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M16.6367 4.59375C17.3398 4.06641 17.9727 3.43359 18.4648 2.69531C17.832 2.97656 17.0938 3.1875 16.3555 3.25781C17.1289 2.80078 17.6914 2.09766 17.9727 1.21875C17.2695 1.64062 16.4609 1.95703 15.6523 2.13281C14.9492 1.39453 14 0.972656 12.9453 0.972656C10.9062 0.972656 9.25391 2.625 9.25391 4.66406C9.25391 4.94531 9.28906 5.22656 9.35938 5.50781C6.30078 5.33203 3.55859 3.85547 1.73047 1.64062C1.41406 2.16797 1.23828 2.80078 1.23828 3.50391C1.23828 4.76953 1.87109 5.89453 2.89062 6.5625C2.29297 6.52734 1.69531 6.38672 1.20312 6.10547V6.14062C1.20312 7.93359 2.46875 9.41016 4.15625 9.76172C3.875 9.83203 3.52344 9.90234 3.20703 9.90234C2.96094 9.90234 2.75 9.86719 2.50391 9.83203C2.96094 11.3086 4.33203 12.3633 5.94922 12.3984C4.68359 13.3828 3.10156 13.9805 1.37891 13.9805C1.0625 13.9805 0.78125 13.9453 0.5 13.9102C2.11719 14.9648 4.05078 15.5625 6.16016 15.5625C12.9453 15.5625 16.6367 9.97266 16.6367 5.08594C16.6367 4.91016 16.6367 4.76953 16.6367 4.59375Z" fill="#292F36"/>
                        </svg></a>
                    
                        <p class="in">in</p>
                        
                        
                </div>
            </div>
            <ul class="footer__menu">
                <li class="footer__bold">Pages</li>
                <li class="footer__link"><router-link to="/" exact>Home</router-link></li>
                <li class="footer__link"><router-link to="/Project">Project</router-link></li>
                <li class="footer__link"><router-link to="/Blog">Blog</router-link></li>
                
              
            </ul>
            <div class="footer__cont">
                <p class="footer__bold">Contact</p>
                <div class="contacts">                   
                    <p class="contact">55 East Birchwood Ave. Brooklyn, New York 11201 
                        </p>
                        <p class="contact">contact@interno.com</p>
                    <p class="contact">(123) 456 - 7890</p>
                </div>
                
            </div>
        </div>
        
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>