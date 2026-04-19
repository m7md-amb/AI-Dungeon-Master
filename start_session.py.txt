# Use Case: Start Session
# Actor: Player, Game Master

def start_session(player_name, game_master="AI Dungeon Master"):
    print("=" * 40)
    print("   Welcome to the AI Dungeon Master!")
    print("=" * 40)
    print(f"Player: {player_name}")
    print(f"Game Master: {game_master}")
    print("Session started. Good luck, adventurer!")
    print("=" * 40)

player = input("Enter your player name: ")
start_session(player)