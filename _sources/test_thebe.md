# Test Thebe

Ce fichier teste l’activation de Thebe et l’apparition du bouton *Run*.

## Activation Thebe

```{thebe-config}
{
  "requestKernel": true,
  "binderOptions": {
    "repo": "ngAtUbo/Cours_IMQ_binder",
    "ref": "main"
  }
}
```

```{thebe-button}
```

## Cellule exécutable

```{code-cell}
print("Hello depuis Thebe !")
a = 2
b = 3
a + b
```

## Deuxième cellule

```{code-cell}
for i in range(5):
    print("i =", i)
```
