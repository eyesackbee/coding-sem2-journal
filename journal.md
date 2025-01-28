# coding-sem2-journal

this is a general learning journal for my semester 2 coding classes

# 2025-01-28

```c#
public float rotationSpeed;
public Transform gun;

float h = Input.GetAxisRaw("Horizontal");
 transform.Rotate(0,h * rotationSpeed * Time.deltaTime, 0);

 float v = Input.GetAxisRaw("Vertical");
 gun.Rotate(v * rotationSpeed * Time.deltaTime, 0, 0);
```

This code made it so the tutorial model rotated and also moved the top gun on top. I don't understand why.

![image](https://github.com/user-attachments/assets/2b927734-ecc5-48e5-b578-7f5864c177f8)

The float v makes the yellow cap on top move vertically around the sphere, and the float r rotated the entire turret.
