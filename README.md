# Ensamblador 3D

App para Mac (chip Apple o Intel) para importar piezas **STEP**, ensamblarlas uniendo sus agujeros, simular un **cuadrilátero articulado**, animarlo y exportar un vídeo **MP4**.

## Instalar (un solo comando)

Abre **Terminal** (⌘ + espacio → escribe «Terminal» → Intro), pega esta línea y pulsa Intro:

```bash
curl -fL https://github.com/Hadock547/ensamblador-3d/releases/latest/download/Ensamblador-3D-Mac.zip -o /tmp/e3d.zip && ditto -x -k /tmp/e3d.zip /Applications && xattr -cr "/Applications/Ensamblador 3D.app" && open "/Applications/Ensamblador 3D.app"
```

Descarga la app, la instala en **Aplicaciones** y la abre. El mismo comando sirve para actualizarla.

## Piezas de ejemplo

[Piezas-de-ejemplo.zip](https://github.com/Hadock547/ensamblador-3d/releases/latest/download/Piezas-de-ejemplo.zip): barras de 40, 80, 100, 120 y 150 mm y un cuadrilátero ya montado.

## Cómo se usa

1. **＋ Importar STEP** y elige tus piezas.
2. **🔗 Unir agujeros**: clic en el borde del agujero de una pieza y luego en el de la otra. Se pegan cara contra cara.
3. Con 4 uniones en lazo se forma el cuadrilátero: arrastra una barra con el ratón.
4. **② Mover** → ▶ → **⬇ Exportar MP4**.

Atajos: ⌘Z deshacer · ⇧⌘Z rehacer · W mover · E rotar · F encuadrar · Esc cancelar · 📏 Medir distancias entre ejes.
