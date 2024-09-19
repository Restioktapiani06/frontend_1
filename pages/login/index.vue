    <template>
    <div class="container-fluid d-flex justify-content-center align-items-center" style="background-color: #80A1E8;">
            <div class="col-4">
                <div class = "card shadow p-3 rounded-4" style="background-color: #D9D9D9;">
                    <h1 class="text-center">Login MyAdmin</h1>
                    <form class="" action="#" method="post">
                        <label>username</label>
                        <input type="text" name="username" class="m-3"><br>
                        <label>password</label>
                        <input type="password" name="password" class="m-3"><br>                        
    <div class="d-grid gap-2 d-md-flex justify-content-md-end">
        <button class="btn btn-primary me-md-2" type="button">LOGIN</button>
    </div>
                    </form>
                </div>
            </div>
    </div>
</template>

<style setup>
    .container-fluid{
        height: 100vh;
    }

    .card{
        height: 300px;
    }
</style>

<script scope>
    definePageMeta({
        layout: 'loginPage'
    })
</script>
