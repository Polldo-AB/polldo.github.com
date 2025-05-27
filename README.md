<input class="search-input placeholder:text-gray-80 mr-5 w-full text-base outline-0 focus:bg-white bg-gray-50" type="text" placeholder="Sök" data-testid="header-search" value="">
<i class="icon-l icon-menu group-data-[state=open]:icon-close"></i>
<!DOCTYPE html>
<html lang="sv">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Hamburgermeny</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
    }

    .menu-container {
      position: relative;
      padding: 1rem;
      background-color: #000;
    }

    .menu-button {
      font-size: 1.8rem;
      color: #fff;
      background: none;
      border: none;
      cursor: pointer;
    }

    .menu-links {
      display: none;
      flex-direction: column;
      background-color: #fff;
      position: absolute;
      top: 60px;
      left: 10px;
      box-shadow: 0 4px 8px
