<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8" />
		<meta http-equiv="X-UA-Compatible" content="IE=edge" />
		<meta name="viewport"content="width=device-width, initial-scale=1.0"/>
		<title>Tienda</title>
		<link rel="stylesheet" href="styles.css" />
	</head>
	<body>
		<header>
		<div class="contenedor">
			<h1>Venta en linea</h1>

			<div class="container-icon">
				<div class="container-cart-icon">
					<svg
						xmlns="http://www.w3.org/2000/svg"
						fill="none"
						viewBox="0 0 24 24"
						stroke-width="1.5"
						stroke="currentColor"
						class="icon-cart"
					>
						<path
							stroke-linecap="round"
							stroke-linejoin="round"
							d="M15.75 10.5V6a3.75 3.75 0 10-7.5 0v4.5m11.356-1.993l1.263 12c.07.665-.45 1.243-1.119 1.243H4.25a1.125 1.125 0 01-1.12-1.243l1.264-12A1.125 1.125 0 015.513 7.5h12.974c.576 0 1.059.435 1.119 1.007zM8.625 10.5a.375.375 0 11-.75 0 .375.375 0 01.75 0zm7.5 0a.375.375 0 11-.75 0 .375.375 0 01.75 0z"
						/>
					</svg>
					<div class="count-products">
						<span id="contador-productos">0</span>
					</div>
				</div>

				<div class="container-cart-products hidden-cart">
					<div class="row-product hidden">
						<div class="cart-product">
							<div class="info-cart-product">
								<span class="cantidad-producto-carrito">1</span>
								<p class="titulo-producto-carrito">Panela</p>
								<span class="precio-producto-carrito">$1</span>
							</div>
							<svg
								xmlns="http://www.w3.org/2000/svg"
								fill="none"
								viewBox="0 0 24 24"
								stroke-width="1.5"
								stroke="currentColor"
								class="icon-close"
							>
								<path
									stroke-linecap="round"
									stroke-linejoin="round"
									d="M6 18L18 6M6 6l12 12"
								/>
							</svg>
						</div>
					</div>

					<div class="cart-total hidden">
						<h3>Total:</h3>
						<span class="total-pagar">$200</span>
					</div>
					<p class="cart-empty">El carrito está vacío</p>
				</div>
			</div>
		</header>
		<div class="container-items">
			<div class="item">
				<figure>
					<img
						src="panela.jpeg"
						alt="producto"
					/>
				</figure>
				<div class="info-product">
					<h2>Panela</h2>
					<p class="price">$1</p>
					<button class="btn-add-cart">Añadir al carrito</button>
				</div>
			</div>
			<div class="item">
				<figure>
					<img
						src="machica fina.jpeg"
						alt="producto"
					/>
				</figure>
				<div class="info-product">
					<h2>Machica Fina</h2>
					<p class="price">$1.25</p>
					<button class="btn-add-cart">Añadir al carrito</button>
				</div>
			</div>
			<div class="item">
				<figure>
					<img
						src="machica gruesa.jpg"
						alt="producto"
					/>
				</figure>
				<div class="info-product">
					<h2>Machica Gruesa</h2>
					<p class="price">$1.25</p>
					<button class="btn-add-cart">Añadir al carrito</button>
				</div>
			</div>
			<div class="item">
				<figure>
					<img
						src="harina de maiz.jpeg"
						alt="producto"
					/>
				</figure>
				<div class="info-product">
					<h2>Harina de Maiz</h2>
					<p class="price">$1.50</p>
					<button class="btn-add-cart">Añadir al carrito</button>
				</div>
			</div>
			<div class="item">
				<figure>
					<img
						src="harina de trigo.jpeg"
						alt="producto"
					/>
				</figure>
				<div class="info-product">
					<h2>Harina de Trigo</h2>
					<p class="price">$1.50</p>
					<button class="btn-add-cart">Añadir al carrito</button>
				</div>
			</div>
			<div class="item">
				<figure>
					<img
						src="harina de cauca.jpg"
						alt="producto"
					/>
				</figure>
				<div class="info-product">
					<h2>Harina de Cauca</h2>
					<p class="price">$1.50</p>
					<button class="btn-add-cart">Añadir al carrito</button>
				</div>
			</div>
			<div class="item">
				<figure>
					<img
						src="harina de alverja.jpeg"
						alt="producto"
					/>
				</figure>
		</div>
		<div class="info-product">
					<h2>Harina de Alverja</h2>
					<p class="price">$1.50</p>
					<button class="btn-add-cart">Añadir al carrito</button>
				</div>
			</div>
			<div class="item">
				<figure>
					<img
						src="harina de abilla.jpeg"
						alt="producto"
					/>
				</figure>
		</div>
		<div class="info-product">
					<h2>Harina de Abilla</h2>
					<p class="price">$1.50</p>
					<button class="btn-add-cart">Añadir al carrito</button>
				</div>
			</div>
			<div class="item">
				<figure>
					<img
						src="harina de haba.jpeg"
						alt="producto"
					/>
				</figure>
		</div>
		<div class="info-product">
					<h2>Harina de Haba</h2>
					<p class="price">$1.50</p>
					<button class="btn-add-cart">Añadir al carrito</button>
				</div>
			</div>
			<div class="item">
				<figure>
					<img
						src="jugo de mashua.jpg"
						alt="producto"
					/>
				</figure>
		</div>
		<div class="info-product">
					<h2>Jugo de Mashua</h2>
					<p class="price">$0.50</p>
					<button class="btn-add-cart">Añadir al carrito</button>
				</div>
			</div>
			<div class="item">
				<figure>
					<img
						src="descarga.jpg"
						alt="producto"
					/>
				</figure>
		</div>
		<div class="info-product">
					<h2>Agua de Sabila </h2>
					<p class="price">$1</p>
					<button class="btn-add-cart">Añadir al carrito</button>
				</div>
			</div>

		<script src="index.js"></script>
	</body>
</html>

<!---
Elena21XD/Elena21XD is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
