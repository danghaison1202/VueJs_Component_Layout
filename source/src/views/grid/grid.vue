
import Vue from 'vue/types/umd';
<template>
    <div class="container">
        <h2>Dynamic FE Layout</h2>
        <div class="item1 item">item 1
            <div v-if="Visible" class="card">
                <div  class="card-info">
                    <p class="title">Magic Card</p>
                </div>
                
            </div>
            <div v-else class="card2">
                    <p  class="card-title">Product Name</p>
                    <p class="small-desc">
                        VueJs Competency Test
                    </p>
                    <div class="go-corner">
                        <div class="go-arrow">→</div>
                    </div>
                </div>
            <div>
                <button @click="Visible = !Visible">Toggle Component</button>
            </div>
        </div>
        <div class="item2 item">item 2

        </div>
        <div class="item3 item">item 3
            <div class="card2">
                <p class="card-title">Product Name</p>
                <p class="small-desc">
                    VueJs Competency Test
                </p>
                <div class="go-corner">
                    <div class="go-arrow">→</div>
                </div>
            </div>
        </div>
        <div class="item4 item">item 4</div>
        <div class="item5 item">item 5</div>
    </div>
</template>
<script>
export default {
    data() {
        return {
            Visible: true
        }
    }
}
</script>