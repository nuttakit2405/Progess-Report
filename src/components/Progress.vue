<template>
    <section>

        <b-collapse class="card">
            <div slot="trigger" slot-scope="props" class="card-header">
                <p class="card-header-title">
                    รายงานความก้าวหน้า ครั้งที่1
                </p>
                <a class="card-header-icon">
                    <b-icon
                        :icon="props.open ? 'menu-down' : 'menu-up'">
                    </b-icon>
                </a>
            </div>
            <div class="card-content">
                <div class="content">
                    รายละเอียดความก้าวหน้า
                </div>
            </div>
            <footer class="card-footer">
                <a class="card-footer-item">Save</a>
                <a class="card-footer-item">Edit</a>
                <a class="card-footer-item">Delete</a>
            </footer>
        </b-collapse> <br>

        <b-collapse class="card">
            <div slot="trigger" slot-scope="props" class="card-header">
                <p class="card-header-title">
                    รายงานความก้าวหน้า ครั้งที่1
                </p>
                <a class="card-header-icon">
                    <b-icon
                        :icon="props.open ? 'menu-down' : 'menu-up'">
                    </b-icon>
                </a>
            </div>
            <div class="card-content">
                <div class="content">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris.
                    <a>#buefy</a>.
                </div>
            </div>
            <footer class="card-footer">
                <a class="card-footer-item">Save</a>
                <a class="card-footer-item">Edit</a>
                <a class="card-footer-item">Delete</a>
            </footer>
        </b-collapse>
    </section>
</template>
