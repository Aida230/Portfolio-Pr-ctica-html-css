.banner {
    height: 30vh;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    overflow: hidden;

    .content {
        color: rgb(5, 236, 253);
        background-color: rgba(9, 1, 1, 0.436);
        border-radius: 10px;
        display: inline-block;
    }

    .image {
        img {
            z-index: -1;
            max-width: 100%;
            height: auto;
            position: absolute;
            top: 0;
            left: 0;
        }
    }
}



        <div>
            <label for="opciones">Como me conociste?</label>
            <input type="radio" id="opciones" name="opciones" value="opciones" checked>
                <li>Dentro de la muralla María</li>
                <li>Cadetes en el equipo de exploración</li>
                <li>Fuera de los muros</li>
                <li>Luchando contra los titanes</li>
            </ul>
        </div>






