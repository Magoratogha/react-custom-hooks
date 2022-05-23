# useForm Hook

Example of use:

```
    const initialForm = {
        name: '',
        age: 0,
        email: ''
    };
    const [ formValue, handleValueChange, resetValues ] = useForm(initialForm);
```