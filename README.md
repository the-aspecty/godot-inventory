# Godot Complete Inventory System

:warning: WIP

A comprehensive inventory system for Godot 4.x with modding support, written in C#.

## Features

- **Inventory Management**
  - Flexible grid-based inventory system
  - Item stacking and splitting
  - Drag and drop functionality
  - Weight and capacity limits
  
- **Item System**
  - Item categories and types
  - Custom item properties
  - Item rarity system
  - Item durability
  - Equipment slots

- **Hotbar System**
  - Customizable hotbar slots
  - Quick item access
  - Hotkey support
  
- **Crafting System**
  - Recipe-based crafting
  - Multiple crafting categories
  - Crafting requirements
  - Success chance system
  
- **Technology System**
  - Tech tree progression
  - Unlock new recipes and items
  - Research requirements
  
- **Registry System**
  - Centralized item registration
  - Resource Loading
  - Display Item Information
  - Mod content support
  
- **Modding API**
  - Custom item creation
  - Recipe modification
  - Tech tree expansion
  - Event hooks for inventory actions

## Getting Started

1. Copy the inventory system files to your Godot project
2. Add the necessary scenes to your game
3. Configure the system through the provided settings files

## Documentation

### Basic Usage

```csharp
// Example: Creating a new inventory
var inventory = new Inventory(5); 
inventory.AddItem(new Item("sword"));

// Example: Creating a custom recipe
var recipe = new Recipe("iron_sword")
    .AddIngredient("iron_ingot", 2)
    .AddIngredient("stick", 1);

// Example: Registering mod content
ModRegistry.RegisterItem(new ModItem("custom_sword"));
```

<!-- ### API Reference

See the [API Documentation](docs/API.md) for detailed information about:
- Inventory management
- Item creation
- Recipe system
- Technology tree
- Modding interfaces -->

## License

MIT License - See LICENSE file for details
