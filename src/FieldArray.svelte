<script>
  console.log('my-new-component  FieldArray')
  let names = ['a']

  const callback = () => {
    names = ['a', 'b']
    // console.log(`FieldArray fieldState for ${name}:`, fields.names())
  }

  setTimeout(callback, 0);
</script>

<slot names={names} />
