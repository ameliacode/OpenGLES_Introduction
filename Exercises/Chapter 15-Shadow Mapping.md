## Chapter 15 | Exercises

#### 1.

#### (a) Fully lit: f4, f5, shadowed: f1,f2,f3

#### (b) 0.88

#### 2.

```glsl
void main()
{
    gl_Position = lightProjMat * lightViewMat * worldMat * vec4(position, 1.0);
}
```

