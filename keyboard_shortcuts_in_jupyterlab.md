# Keyboard shortcuts in JupyterLab

Code:

`
{
    "shortcuts": [
    {
      // Hide cells output
      "command": "notebook:hide-cell-outputs",
      "keys": [
        "O"
      ],
      "selector": ".jp-Notebook:focus"
    },    
    {
      // Show cells output
      "command": "notebook:show-cell-outputs",
      "keys": [
        "O",
        "O"
      ],
      "selector": ".jp-Notebook:focus"
    },    

    {
      // Hide all cells outputs
      "command": "notebook:hide-all-cell-outputs",
      "keys": [
        "Shift O"
      ],
      "selector": ".jp-Notebook:focus"
    },
       
    {
      // Show all cells outputs
      "command": "notebook:show-all-cell-outputs",
      "keys": [
        "Ctrl Shift O"
      ],
      "selector": ".jp-Notebook:focus"
    },
       
     {
      // Hide cells code
      "command": "notebook:hide-cell-code",
      "keys": [
        "L"
      ],
      "selector": ".jp-Notebook:focus"
    },    
    {
      // Show cells code
      "command": "notebook:show-cell-code",
      "keys": [
        "L",
        "L"
      ],
      "selector": ".jp-Notebook:focus"
    },

    {
      // Hide all cells code
      "command": "notebook:hide-all-cell-code",
      "keys": [
        "Shift L"
      ],
      "selector": ".jp-Notebook:focus"
    },
       
      {
      // Show all cells codes
      "command": "'notebook:show-all-cell-code",
      "keys": [
        "Ctrl Shift L"
      ],
      "selector": ".jp-Notebook:focus"
    },  
       
      {
      // Move cell up
      "command": "notebook:move-cell-up",
      "keys": [
        "Ctrl ArrowUp"
      ],
      "selector": ".jp-Notebook:focus",
    },

    {
      // Move cell down
      "command": "notebook:move-cell-down",
      "keys": [
        "Ctrl ArrowDown"
      ],
      "selector": ".jp-Notebook:focus",
    }
  ]
}
`