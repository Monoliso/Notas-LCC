---
fecha_creacion: 2023-10-28
---
## Registros a usar

The eight general-purpose registers in the x86 processor family each have a unique purpose. Each register has special instructions and opcodes which make fulfilling this purpose more convenient or efficient. The registers and their uses are shown briefly below:

- EAX - All major calculations take place in EAX, making it similar to a dedicated accumulator register.
- EDX - The data register is the an extension to the accumulator. It is most useful for storing data related to the accumulator's current calculation.
- ECX - Like the variable i in high-level languages, the count register is the universal loop counter.
- EDI - Every loop must store its result somewhere, and the destination index points to that place. With a single-byte STOS instruction to write data out of the accumulator, this register makes data operations much more size-efficient.
- ESI - In loops that process data, the source index holds the location of the input data stream. Like the destination index, EDI has a convenient one-byte instruction for loading data out of memory into the accumulator.
- ESP - ESP is the sacred stack pointer. With the important PUSH, POP, CALL, and RET instructions requiring it's value, there is never a good reason to use the stack pointer for anything else.
- EBP - In functions that store parameters or variables on the stack, the base pointer holds the location of the current stack frame. In other situations, however, EBP is a free data-storage register.
- EBX - In 16-bit mode, the base register was useful as a pointer. Now it is completely free for extra storage space.

## Ejercicios de interés
- [x] 3
- [x] 5
- [x] 6
- [ ] 7 ❓
- [ ] 9 ❓
- [ ] 10
- [x] 11
- [ ] 15
- [ ] 16
## Revisar
 - [ ] Instrucciones de conversión
 - [ ] Cómo funcionan las banderas en la resta
	 - [ ] Instrucciones para el registro de banderas
 - [x] Instrucción MUL/IMUL, DIV/IDIV

### Banderas (xd)
Las banderas para trabajar con las operaciones sobre números son *Carry Flag* y *Overflow Flag*.
 - La *Carry Flag* avisa que si se interpreta el número como positivo (sin signo) entonces el resultado será erróneo.
 - La *Overflow Flag* avisa que si se interpreta el número como un número con signo entonces el resultado será erróneo.

## Fuentes
 - https://en.wikibooks.org/wiki/X86_Assembly/X86_Architecture. Se trata de la variante Intel, pero es muy útil de todas formas.
 - https://stackoverflow.com/questions/69124873/understanding-the-difference-between-overflow-and-carry-flags