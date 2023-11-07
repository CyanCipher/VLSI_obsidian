In the context of VHDL, entities are descriptions of the interfaces between designs and their external environments. They define the ports of the design, which are the points at which the design communicates with the outside world. Entities can also contain parameters, which are constants that can be used to customize the design.

Entities are declared using the `entity` keyword, followed by the name of the entity and a list of ports. The ports are defined using the `port` keyword, followed by the port name, direction (in, out, or inout), and type.

Here is an example of a simple entity declaration:

VHDL

```
entity inverter is
  port (
    input : in std_logic;
    output : out std_logic
  );
end inverter;
```

This entity declares a design called `inverter` with two ports: `input` and `output`. The `input` port is an input port, and the `output` port is an output port. Both ports are of the type `std_logic`, which is a standard VHDL type for representing logic values.

Entities are important because they allow designers to define the interfaces of their designs without having to worry about the implementation. This makes it easier to reuse designs and to integrate them with other designs.

Here are some of the benefits of using entities:

- **Modularity:** Entities allow designers to create modular designs that can be reused and integrated with other designs.
- **Abstraction:** Entities allow designers to abstract away the implementation details of a design, making it easier to understand and use.
- **Testability:** Entities make it easier to test designs, because the ports of the design can be easily connected to test stimuli.

Overall, entities are an important part of VHDL design. They allow designers to create modular, abstract, and testable designs.