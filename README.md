# Rust

## Cargo

Para ejecutar se utiliza:

```
cargo run
```

> Lo que hace es que compila y ejecuta en un solo comando.


*Nota: si se quiere compilar antes de ejecutar el programa se puede usar el siguiente comando:*

```bash
cargo build
```

> ambos comandos `build` y `run`, dejan el binario que se usa para desarrollo en el directorio `./target/debug/<filename>` -> `./target/debug/hello_world`.


### Check

```bash
cargo check
```

Sirve para comprobar si el codigo compila, sin generar ningun ejecutable (binario).


### build release

```bash
cargo build --release
```

Sirve para compilar el programa con optimizaciones.

El ejecutable se guarda en `target/release`. Este proceso suele tardar mas en producir o crear el binario que utilizar solo `cargo build`.


## rustc

Para compilar
```bash
rustc src/main.rs
```

Luego para ejecutarlo

```bash
./main
```

