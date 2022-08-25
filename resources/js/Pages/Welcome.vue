<script setup>
import { Head, Link } from '@inertiajs/inertia-vue3';
</script>

<template>
    <Head title="Welcome" />

    <div class="fixed top-0 left-0 px-6 py-4 sm:block">
        <Link :href="route('dashboard')" class="text-sm text-gray-700 dark:text-gray-500 underline">Dashboard</Link>
    </div>
    
    <div class="hidden fixed top-0 right-0 px-6 py-4 sm:block">
        <div>
            <Link :href="route('login')" class="text-sm text-gray-700 dark:text-gray-500 underline">Log in</Link>

            <Link :href="route('register')" class="ml-4 text-sm text-gray-700 dark:text-gray-500 underline">Register</Link>
        </div>
    </div>

    <div class="container mt-16">
        <div>
            <Link :href="route('login')" class="text-sm text-gray-700 dark:text-gray-500 underline">
                <div class="btn btn-primary mr-3">ログイン</div>
            </Link>
            
            <Link :href="route('register')" class="ml-4 text-sm text-gray-700 dark:text-gray-500 underline">
                <div class="btn btn-info">新規登録</div>
            </Link>
            
        </div>

        <br>

        <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
                <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner">
                <div class="carousel-item active">
                <img src="https://www.pakutaso.com/shared/img/thumb/elly20160701425018_TP_V.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>First slide label</h5>
                    <p>Some representative placeholder content for the first slide.</p>
                </div>
                </div>
                <div class="carousel-item">
                <img src="https://www.pakutaso.com/shared/img/thumb/51redsugar2286_TP_V.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Second slide label</h5>
                    <p>Some representative placeholder content for the second slide.</p>
                </div>
                </div>
                <div class="carousel-item">
                <img src="https://www.pakutaso.com/shared/img/thumb/redsugar201025983_TP_V.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Third slide label</h5>
                    <p>Some representative placeholder content for the third slide.</p>
                </div>
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
    </div>

    <br>

    <div id="carouselExampleCaptions2" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions2" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions2" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions2" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
            <div class="carousel-item active">
            <img src="https://www.pakutaso.com/shared/img/thumb/30redsugar2286_TP_V.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
                <h5>First slide label</h5>
                <p>Some representative placeholder content for the first slide.</p>
            </div>
            </div>
            <div class="carousel-item">
            <img src="https://www.pakutaso.com/shared/img/thumb/012REDN8IS_TP_V.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
                <h5>Second slide label</h5>
                <p>Some representative placeholder content for the second slide.</p>
            </div>
            </div>
            <div class="carousel-item">
            <img src="https://www.pakutaso.com/shared/img/thumb/RS19413C001_TP_V.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
                <h5>Third slide label</h5>
                <p>Some representative placeholder content for the third slide.</p>
            </div>
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions2" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions2" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>

    <br>

    <div class="container">
        <table class="table">
            <thead>
                <tr>
                <th scope="col">#</th>
                <th scope="col">First</th>
                <th scope="col">Last</th>
                <th scope="col">Handle</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                <th scope="row">1</th>
                <td>Mark</td>
                <td>Otto</td>
                <td>@mdo</td>
                </tr>
                <tr>
                <th scope="row">2</th>
                <td>Jacob</td>
                <td>Thornton</td>
                <td>@fat</td>
                </tr>
                <tr>
                <th scope="row">3</th>
                <td colspan="2">Larry the Bird</td>
                <td>@twitter</td>
                </tr>
            </tbody>
        </table>
    </div>

    <br>

    <div class="container">
        <div class="row" >
            <div class="col text-center">
                <div class="card">
                    <img src="https://dot.asahi.com/S2000/upload/2017011800026_1.jpg" class="card-img-top" style="max-height: 400px" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="https://www.google.co.jp/" class="btn btn-primary">Go somewhere</a>
                    </div>
                </div>
            </div>
            <div class="col text-center">
                <div class="card">
                    <img src="http://bible-cafe.com/wp-content/uploads/2015/04/Nitobe_Inazo.jpg" class="card-img-top" style="max-height: 400px" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                    </div>
                </div>
            </div>
            <div class="col text-center">
                <div class="card">
                    <img src="https://static.tokyo-np.co.jp/image/article/size1/f/c/e/0/fce073de2d07047512a38f19d4a53c16_3.jpg" class="card-img-top" style="max-height: 400px" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                    </div>
                </div>
            </div>
        </div>

        <br>

        <div class="row" >
            <div class="col text-center">
                <div class="card">
                    <img src="https://dot.asahi.com/S2000/upload/2017011800026_1.jpg" class="card-img-top" style="max-height: 400px" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                    </div>
                </div>
            </div>
            <div class="col text-center">
                <div class="card">
                    <img src="http://bible-cafe.com/wp-content/uploads/2015/04/Nitobe_Inazo.jpg" class="card-img-top" style="max-height: 400px" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                    </div>
                </div>
            </div>
            <div class="col text-center">
                <div class="card">
                    <img src="https://static.tokyo-np.co.jp/image/article/size1/f/c/e/0/fce073de2d07047512a38f19d4a53c16_3.jpg" class="card-img-top" style="max-height: 400px" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                    </div>
                </div>
            </div>
        </div>

        <br>

        <div class="row" >
            <div class="col text-center">
                <div class="card">
                    <img src="https://dot.asahi.com/S2000/upload/2017011800026_1.jpg" class="card-img-top" style="max-height: 400px" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                    </div>
                </div>
            </div>
            <div class="col text-center">
                <div class="card">
                    <img src="http://bible-cafe.com/wp-content/uploads/2015/04/Nitobe_Inazo.jpg" class="card-img-top" style="max-height: 400px" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                    </div>
                </div>
            </div>
            <div class="col text-center">
                <div class="card">
                    <img src="https://static.tokyo-np.co.jp/image/article/size1/f/c/e/0/fce073de2d07047512a38f19d4a53c16_3.jpg" class="card-img-top" style="max-height: 400px" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                    </div>
                </div>
            </div>
        </div>



    </div>

    <br>

    <div class="container text-center">
        <!-- Button trigger modal -->
        <a href="" class="btn btn-danger" data-bs-toggle="modal" data-bs-target="#exampleModal">Go modal</a>
    </div>

    <!-- Modal -->
    <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
        <div class="modal-dialog modal-dialog-centered modal-dialog-scrollable">
            <div class="modal-content">
            <div class="modal-header">
                <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
            </div>
            <div class="modal-body">
                テキストテキストテキストテキストテキストテキスト
                テキストテキストテキストテキストテキストテキスト
                テキストテキストテキストテキストテキストテキスト
                テキストテキストテキストテキストテキストテキスト

                テキストテキストテキストテキストテキストテキスト
                テキストテキストテキストテキストテキストテキスト
            </div>
            <div class="modal-footer">
                <a href="" class="btn btn-secondary" data-bs-dismiss="modal">Close</a>
                <a href="" class="btn btn-primary">Save changes</a>
            </div>
            </div>
        </div>
    </div>

    <br>

    <footer class="footer mt-4 py-3 bg-light">
        <div class="container text-center">
        <span class="text-muted">Demo Company &copy; All Right Reserved.</span>
        </div>
    </footer>


</template>

