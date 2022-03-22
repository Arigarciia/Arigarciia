Oiii!!! Meu nome é Ariane Garcia 

Sou apaixonada pela área tech recruiter e meu intuito é encantar futuros candidados 
Hoje trabalho em sourcing com foco em mobile 
https://www.linkedin.com/in/ariane-s%C3%A1/

 name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Summary Cards
      - uses: actions/checkout@v2
      - uses: vn7n24fzkq/github-profile-summary-cards@release
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        with:
          USERNAME: ${{ github.repository_owner }}

      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
  # Snake Animation
  - uses: Platane/snk@master
    id: snake-gif
