# Messenger-Elixir

## Introduction

Welcome to `messenger-elixir`, a repository created for the purpose of exploring and understanding the capabilities of [Phoenix LiveView](https://hexdocs.pm/phoenix_live_view/Phoenix.LiveView.html). Phoenix LiveView is a powerful Elixir framework that enables rich, real-time user experiences with server-rendered HTML. This project aims to demonstrate the advantages of LiveView in web development through the creation of a simple messenger application.

## Project Overview

The `messenger-elixir` project is a messaging platform where users can send and receive messages in real-time. It leverages the Phoenix LiveView framework to create an interactive, seamless user experience without the need for JavaScript heavy front-end frameworks.

### Key Features

- Real-time messaging: Users can send and receive messages instantly.
- Live updates: User interface updates dynamically as new messages arrive.
- Minimal JavaScript: Majority of the interactivity handled server-side by Phoenix LiveView.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following installed:

- [Elixir](https://elixir-lang.org/install.html)
- [Phoenix Framework](https://www.phoenixframework.org/docs/installation)
- [PostgreSQL](https://www.postgresql.org/download/)

### Installation

1. Clone the repository:
```sh
% git clone https://github.com/yourusername/messenger-elixir.git
```

2. Navigate to the project directory:
```sh 
% cd messenger-elixir
```

3. Install dependencies:
```sh
mix deps.get
```

4. Create and migrate your database:
```sh
mix exto.setup
```

5. Start the Phoenix Server: 
```sh
mix phx.server
```

6. Visit `localhost:4000` from your browser.
