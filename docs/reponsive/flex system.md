---
sidebar_position: 1
---

# flex system

<div class="container">
    <div class="text-center row">
        <div class="xs:flex-1 box">box</div>
        <div class="xs:flex-11 box">box</div>
        <div class="xs:flex-2 box">box</div>
        <div class="xs:flex-10 box">box</div>
        <div class="xs:flex-3 box">box</div>
        <div class="xs:flex-9 box">box</div>
        <div class="xs:flex-4 box">box</div>
        <div class="xs:flex-8 box">box</div>
        <div class="xs:flex-5 box">box</div>
        <div class="xs:flex-7 box">box</div>
        <div class="xs:flex-6 box">box</div>
        <div class="xs:flex-6 box">box</div>
        <div class="xs:flex-12 box">box</div>
    </div>
</div>

<hr class="mx-2"/>

```html
<div class="row">
  <div class="xs:flex-1">box</div>
  <div class="xs:flex-11">box</div>
  <div class="xs:flex-2">box</div>
  <div class="xs:flex-10">box</div>
  <div class="xs:flex-3">box</div>
  <div class="xs:flex-9">box</div>
  <div class="xs:flex-4">box</div>
  <div class="xs:flex-8">box</div>
  <div class="xs:flex-5">box</div>
  <div class="xs:flex-7">box</div>
  <div class="xs:flex-6">box</div>
  <div class="xs:flex-6">box</div>
  <div class="xs:flex-12">box</div>
</div>
```

<hr class="mx-2"/>

<div class="container">
    <div class="text-center row">
		<div class="xs:flex-12 md:flex-4 sm:flex-6 box lg:flex-1">box</div>
		<div class="xs:flex-12 md:flex-4 sm:flex-6 box lg:flex-11">box</div>
		<div class="xs:flex-12 md:flex-4 sm:flex-6 box lg:flex-2">box</div>
		<div class="xs:flex-12 md:flex-4 sm:flex-6 box lg:flex-10">box</div>
		<div class="xs:flex-12 md:flex-4 sm:flex-6 box lg:flex-3">box</div>
		<div class="xs:flex-12 md:flex-4 sm:flex-6 box lg:flex-9">box</div>
		<div class="xs:flex-12 md:flex-4 sm:flex-6 box lg:flex-4">box</div>
		<div class="xs:flex-12 md:flex-4 sm:flex-6 box lg:flex-8">box</div>
		<div class="xs:flex-12 md:flex-4 sm:flex-6 box lg:flex-5">box</div>
		<div class="xs:flex-12 md:flex-4 sm:flex-6 box lg:flex-7">box</div>
		<div class="xs:flex-12 md:flex-4 sm:flex-6 box lg:flex-6">box</div>
		<div class="xs:flex-12 md:flex-4 sm:flex-6 box lg:flex-6">box</div>
    </div>
</div>

<hr class="mx-2"/>

```html
<div class="row">
  <div class="xs:flex-12 md:flex-4 sm:flex-6 lg:flex-1">box</div>
  <div class="xs:flex-12 md:flex-4 sm:flex-6 lg:flex-11">box</div>
  <div class="xs:flex-12 md:flex-4 sm:flex-6 lg:flex-2">box</div>
  <div class="xs:flex-12 md:flex-4 sm:flex-6 lg:flex-10">box</div>
  <div class="xs:flex-12 md:flex-4 sm:flex-6 lg:flex-3">box</div>
  <div class="xs:flex-12 md:flex-4 sm:flex-6 lg:flex-9">box</div>
  <div class="xs:flex-12 md:flex-4 sm:flex-6 lg:flex-4">box</div>
  <div class="xs:flex-12 md:flex-4 sm:flex-6 lg:flex-8">box</div>
  <div class="xs:flex-12 md:flex-4 sm:flex-6 lg:flex-5">box</div>
  <div class="xs:flex-12 md:flex-4 sm:flex-6 lg:flex-7">box</div>
  <div class="xs:flex-12 md:flex-4 sm:flex-6 lg:flex-6">box</div>
  <div class="xs:flex-12 md:flex-4 sm:flex-6 lg:flex-6">box</div>
</div>
```

<hr class="mx-2"/>

<div class="container">
	<div class="row gap-3 xs:justify-center">
		<div class="card shadowed md:flex-5 sm:flex-5 xs:flex-12">
			<div class="card-title">T shart</div>
				<div class="card-body">
					<img src="https://m.media-amazon.com/images/I/81NTsOeOs+L._AC_SX522._SX._UX._SY._UY_.jpg"/>
					<h3 class="">product for show</h3>
      <button class="btn-flat-blue xs:col-12 sm:col-6">buy</button>
      <button class="btn-flat-red xs:col-12 sm:col-5">
						<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-bag-heart" viewBox="0 0 16 16"><path fill-rule="evenodd" d="M10.5 3.5a2.5 2.5 0 0 0-5 0V4h5v-.5Zm1 0V4H15v10a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V4h3.5v-.5a3.5 3.5 0 1 1 7 0ZM14 14V5H2v9a1 1 0 0 0 1 1h10a1 1 0 0 0 1-1ZM8 7.993c1.664-1.711 5.825 1.283 0 5.132-5.825-3.85-1.664-6.843 0-5.132Z"/></svg>
					</button>
				</div>
			</div>
			<div class="card md:flex-5 sm:flex-5 xs:flex-12">
			<div class="card-title">T shart</div>
				<div class="card-body">
					<img src="https://m.media-amazon.com/images/I/81NTsOeOs+L._AC_SX522._SX._UX._SY._UY_.jpg"/>
					<h3 class="">product for show</h3>
      <button class="btn-flat-blue xs:col-12 sm:col-6">buy</button>
      <button class="btn-flat-red xs:col-12 sm:col-5">
						<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-bag-heart" viewBox="0 0 16 16"><path fill-rule="evenodd" d="M10.5 3.5a2.5 2.5 0 0 0-5 0V4h5v-.5Zm1 0V4H15v10a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V4h3.5v-.5a3.5 3.5 0 1 1 7 0ZM14 14V5H2v9a1 1 0 0 0 1 1h10a1 1 0 0 0 1-1ZM8 7.993c1.664-1.711 5.825 1.283 0 5.132-5.825-3.85-1.664-6.843 0-5.132Z"/></svg>
					</button>
				</div>
			</div>
		</div>
</div>

<hr class="mx-2"/>



```html
<div class="row gap-3 xs:justify-center">
  <div class="card md:flex-5 sm:flex-5 xs:flex-12">
    <div class="card-title">T shart</div>
    <div class="card-body">
      <img src="..." />
      <h3>product for show</h3>
      <button class="btn-flat-blue xs:col-12 sm:col-6">buy</button>
      <button class="btn-flat-red xs:col-12 sm:col-5"><svg></svg></button>
    </div>
  </div>
</div>
```
