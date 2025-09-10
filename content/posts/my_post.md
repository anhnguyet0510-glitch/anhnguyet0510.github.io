+++
date = '2025-09-10T09:37:09+07:00'

title = 'My post'
+++

```wavedrom
{signal: [
  {name: 'clock',   wave: 'p................'},
  {name: 'hwrite',  wave: 'x0x.0x..0.x.0.x..'},
  {name: 'htrans',  wave: 'x3x.4x..5.x.6.x..', data: '2 2 2 2'},
  {name: 'haddr',   wave: 'x3x.4x..5.x.6.x..', data: 'A0 A1 A2 A3'},
  {},
  {name: 'hready',  wave: 'x1.x101x01.x0101x'},
  {name: 'hrdata',  wave: 'x.3x..4x..5x...6x', data: 'D0 D1 D2 D3'},
],
    head: {tock: 1},
    gaps: '( . . 1 . s . 1 s . . 1 s . s . )',
    foot: {text: 'reads'}
}
```