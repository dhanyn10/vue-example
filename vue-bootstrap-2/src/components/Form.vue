<template>
    <div>
        <b-form>
            <b-form-group
                label="email address"
            >
                <b-form-input
                    type="email"
                    placeholder="enter email"
                ></b-form-input>
            </b-form-group>
        </b-form>
    </div>
</template>

<script>
import Vue from 'vue'
import { BForm, BFormGroup, BFormInput } from 'bootstrap-vue'
Vue.component('b-form', BForm)
Vue.component('b-form-group', BFormGroup)
Vue.component('b-form-input', BFormInput)
export default {
    name: 'Form'
}
</script>