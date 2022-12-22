# component-modal-dropdown-datepicker-tailwind-css

Library with modal content, dropdown and datePicker for easy use 


## for install 

```bash
 npm install @bryan__parisot/component-modal-dropdown-datepicker-tailwind-css
```



### Dropdown use

#### props: 
  - selected 
  - setSelected
  - label,
  - options,
  - placeholder,
  - name,
  - onChange,

 #### Example :
```bash
            <Dropdown
              placeholder="Choose your state"
              setSelected={setState}
              selected={state.name}
              options={states}
              label="State"
              name="State"
              onChange={(e) => e.target.value}
            />

```

### datePicker use

#### props: 
  - value 
  - label,
  - name,
  - onChange,

 #### Example :
```bash
            <DatePickers
              name="startDate"
              label="Start Date"
              onChange={(e) => setStartDate(e.target.value)}
              value={startDate}
            />


```

Just add your array in options


### Modal

#### props: 

  - title,
  - subtitle,
  - button,
  - displayModal

#### Example :
```bash
         <Modal
          title="Users create"
          subtitle=" You can access the users in the
                    employees"
          button="Back to employee creation"
          displayModal={setValidate}
        />

```

## Tech Stack

**Client:** React, tailwind css


## Authors

- [@ParisotBryan](https://github.com/BryanParisot)


## If you check the [repository ](https://github.com/BryanParisot/component-modal-dropdown-datepicker-tailwind-css)





