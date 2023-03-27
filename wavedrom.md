```wavedrom
{ signal : [
{ name: "clk",  wave: "p......" },
{ name: "bus",  wave: "x.34.5x",   data: "head body tail" },
{ name: "wire", wave: "0.1..0." },
]}
```

```wavedrom
{ signal: [
{ name: "CK",   wave: "P.......",                                              period: 2  },
{ name: "CMD",  wave: "x.3x=x4x=x=x=x=x", data: "RAS NOP CAS NOP NOP NOP NOP", phase: 0.5 },
{ name: "ADDR", wave: "x.=x..=x........", data: "ROW COL",                     phase: 0.5 },
{ name: "DQS",  wave: "z.......0.1010z." },
{ name: "DQ",   wave: "z.........5555z.", data: "D0 D1 D2 D3" }
]}
```
