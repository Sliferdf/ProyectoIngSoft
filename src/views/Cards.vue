<template>
    <div class="mt-5">
        <b-button variant="warning">Texto</b-button>
        <b-button variant="primary">Primary</b-button>
        <b-button variant="secondary">Secondary</b-button>
        <b-button variant="success">Success</b-button>
        <b-button variant="danger">Danger</b-button>
        <b-button variant="dark">Warning</b-button>
        <b-button variant="info">Info</b-button>

        <b-row class="mt-5">
            <b-col cols="12" md="4">
                <b-card
                title="Card Title"
                img-src="https://picsum.photos/600/300/?image=25"
                img-alt="Image"
                img-top
                tag="article"
                style="max-width: 20rem;"
                class="mb-2"
                >
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dicta pariatur quam deleniti, molestiae omnis commodi iste laborum numquam nemo a quisquam laudantium cumque saepe, accusamus facilis inventore quod culpa minus.</p>
                <b-button href="#" variant="warning">Texto</b-button>
                </b-card>
            </b-col>
             <b-col cols="12" md="4">
                <b-card
                title="Card Title"
                img-src="https://picsum.photos/600/300/?image=25"
                img-alt="Image"
                img-top
                tag="article"
                style="max-width: 20rem;"
                class="mb-2"
                >
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dicta pariatur quam deleniti, molestiae omnis commodi iste laborum numquam nemo a quisquam laudantium cumque saepe, accusamus facilis inventore quod culpa minus.</p>
                <b-button href="#" variant="warning">Texto</b-button>
                </b-card>

            </b-col>
             <b-col cols="12" md="4">
                <b-card
                title="Card Title"
                img-src="https://picsum.photos/600/300/?image=25"
                img-alt="Image"
                img-top
                tag="article"
                style="max-width: 20rem;"
                class="mb-2"
                >
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dicta pariatur quam deleniti, molestiae omnis commodi iste laborum numquam nemo a quisquam laudantium cumque saepe, accusamus facilis inventore quod culpa minus.</p>
                <b-button href="#" variant="warning">Texto</b-button>
                </b-card>

            </b-col>
        </b-row>
    </div>
</template>
<script>
export default {
    name:'Cards'
}
</script>