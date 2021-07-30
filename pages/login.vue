<template>
    <div class="d-flex justify-content-center">
        <div class="section-all section-desktop section-tablet text-center">
            <!-- Arrow Icon -->
            <nuxt-link to="/">
                <svg class="arrow-icon" xmlns="http://www.w3.org/2000/svg" data-name="Layer 1" viewBox="0 0 24 24" width="24px" height="24px"><path fill="#14213D" d="M17,11H9.41l3.3-3.29a1,1,0,1,0-1.42-1.42l-5,5a1,1,0,0,0-.21.33,1,1,0,0,0,0,.76,1,1,0,0,0,.21.33l5,5a1,1,0,0,0,1.42,0,1,1,0,0,0,0-1.42L9.41,13H17a1,1,0,0,0,0-2Z"/>
                </svg>
            </nuxt-link>

            <!-- Register Illustration -->
            <svg class="login-illustration" width="150" height="150" viewBox="0 0 150 150" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M113.15 33.2498C112.569 32.7799 111.891 32.4462 111.164 32.2731C110.437 32.1001 109.681 32.0921 108.95 32.2498C103.607 33.3696 98.092 33.3838 92.7434 32.2918C87.3949 31.1997 82.3265 29.0244 77.8503 25.8998C77.0133 25.3192 76.0189 25.0081 75.0003 25.0081C73.9816 25.0081 72.9873 25.3192 72.1503 25.8998C67.6741 29.0244 62.6056 31.1997 57.2571 32.2918C51.9086 33.3838 46.3931 33.3696 41.0503 32.2498C40.32 32.0921 39.5636 32.1001 38.8368 32.2731C38.11 32.4462 37.4312 32.7799 36.8503 33.2498C36.2702 33.7204 35.8029 34.315 35.4827 34.9899C35.1626 35.6648 34.9977 36.4029 35.0003 37.1498V74.3998C34.9958 81.5686 36.7041 88.6347 39.9829 95.0096C43.2618 101.385 48.0162 106.884 53.8503 111.05L72.1003 124.05C72.9471 124.653 73.9608 124.977 75.0003 124.977C76.0398 124.977 77.0535 124.653 77.9003 124.05L96.1503 111.05C101.984 106.884 106.739 101.385 110.018 95.0096C113.296 88.6347 115.005 81.5686 115 74.3998V37.1498C115.003 36.4029 114.838 35.6648 114.518 34.9899C114.198 34.315 113.73 33.7204 113.15 33.2498ZM105 74.3998C105.004 79.9736 103.677 85.4677 101.129 90.4249C98.5803 95.3821 94.8851 99.6591 90.3503 102.9L75.0003 113.85L59.6503 102.9C55.1155 99.6591 51.4202 95.3821 48.872 90.4249C46.3238 85.4677 44.9964 79.9736 45.0003 74.3998V42.8998C55.4824 43.797 65.9805 41.3649 75.0003 35.9498C84.0201 41.3649 94.5181 43.797 105 42.8998V74.3998Z" fill="#14213D"/>
            <ellipse opacity="0.48" cx="133.125" cy="22.5" rx="7.5" ry="7.5" fill="#FCA311"/>
            <ellipse opacity="0.48" cx="14.0625" cy="84.375" rx="4.6875" ry="4.6875" fill="#FCA311"/>
            <ellipse opacity="0.48" cx="122.812" cy="115.312" rx="4.68749" ry="4.6875" fill="#FCA311"/>
            <path d="M70 68.125C69.31 68.1254 68.7504 67.5664 68.75 66.8764C68.75 66.876 68.75 66.8755 68.75 66.875V63.125C68.7515 59.6717 71.5523 56.8735 75.0056 56.875C76.6586 56.8757 78.2441 57.531 79.4153 58.6975C80.2028 59.4923 80.7663 60.4811 81.0486 61.5638C81.2215 62.2323 80.8197 62.9144 80.1512 63.0873C79.4827 63.2603 78.8006 62.8585 78.6277 62.19C78.6274 62.1887 78.627 62.1875 78.6267 62.1863C78.457 61.5353 78.1184 60.9408 77.6453 60.4626C76.1732 59.0034 73.7969 59.0138 72.3377 60.4859C71.6417 61.188 71.2508 62.1364 71.25 63.125V66.875C71.2504 67.565 70.6914 68.1246 70.0014 68.125C70.0009 68.125 70.0005 68.125 70 68.125ZM76.875 72.5C76.875 71.4645 76.0355 70.625 75 70.625C73.9645 70.625 73.125 71.4645 73.125 72.5C73.125 73.0531 73.369 73.5452 73.75 73.8884V75.625C73.75 75.6255 73.75 75.6259 73.75 75.6265C73.7504 76.3164 74.3101 76.8754 75 76.875C75.0005 76.875 75.0009 76.875 75.0014 76.875C75.6914 76.8746 76.2504 76.3149 76.25 75.625V73.8884C76.631 73.5452 76.875 73.0531 76.875 72.5Z" fill="#FED38D"/>
            <path d="M81.25 65.625H68.75C66.6789 65.625 65 67.3039 65 69.375V78.125C65 80.1961 66.6789 81.875 68.75 81.875H81.25C83.3211 81.875 85 80.1961 85 78.125V69.375C85 67.3039 83.3211 65.625 81.25 65.625ZM76.25 73.8884V75.625C76.2504 76.3149 75.6914 76.8746 75.0015 76.875C75.0009 76.875 75.0005 76.875 75 76.875C74.3101 76.8754 73.7504 76.3164 73.75 75.6265C73.75 75.6259 73.75 75.6255 73.75 75.625V73.8884C73.369 73.5452 73.125 73.0531 73.125 72.5C73.125 71.4645 73.9645 70.625 75 70.625C76.0355 70.625 76.875 71.4645 76.875 72.5C76.875 73.0531 76.631 73.5452 76.25 73.8884Z" fill="#FCA311"/>
            </svg>

            
            <!-- Headline -->
            <div>
                <h4 class="headline">Please Log In!</h4>
                <p class="sub-headline">Fill below to login your account!</p>
            </div>

            <!-- Forms -->
            <form class="input-container " @submit.prevent="userLogin()">
                <div class="input-group">
                    <i class="icon-container uil uil-envelope"></i>
                    <input 
                        v-model="email"
                        type="email" 
                        class="form-control" 
                        placeholder="Email"
                    />
                </div>
                <div class="input-group">
                    <i class="icon-container uil uil-lock"></i>
                    <input 
                        v-model="password"
                        type="password" 
                        class="form-control" 
                        placeholder="Password"
                    />
                </div>
                <nuxt-link class="forgot-button" to="/forgot">Forgot password?</nuxt-link>
                <button @click="onClick" type="submit" class="btn btn-login">LOGIN</button>
            </form>
            <p class="p-register">Don't have an account? <nuxt-link class="btn-register" to="/register"> Register</nuxt-link></p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Login',
    components: { },
    data() {
        return {
            email: '',
            password: ''
        }
    },

    methods: {
        userLogin() {
        const formLogin = {
            email: this.email,
            password: this.password,
        }
        this.$axios
            .post('https://oryx.thunderlab.id/account/login', formLogin)
            .then((res) => {
                console.log(res)
                this.$router.push('/beranda')
            })
            .catch((err) => {
                this.errors = err.response.data.errors
            })
        }
    }
}
</script>

<style scoped>
    svg.arrow-icon {
        display: block;
        margin: 1.5rem 0 0 1.5rem;
    }

    h4.headline {
        margin-top: 1rem;
    }
    
    form.input-container {
        margin-top: 2rem;
    }

    .forgot-button {
        float: right;text-decoration: none;font-size: 15px;color: #14213D;margin-top: .5rem;
    }

    button.btn-login {
        margin-top: 2rem;
    }

    p.p-register {
        margin-top: 2rem;
    }

    .btn-register {
        text-decoration: none;color: #14213D;font-weight: 600;
    }

</style>