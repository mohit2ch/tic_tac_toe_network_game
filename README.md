# tic_tac_toe_network_game

Multiplayer tictactoe Online

Api List 
Client side:
connect_to_server(name)
receive_message_from_server(sck, m)
game_logic() 
	Server side:
start_server()
stop_server()
accept_clients(the_server, y)
update_client_names_display(name_list)
get_client_index(client_list, curr_client)
send_receive_client_message(client_connection, client_ip_addr)
b. Objects
	Client side:
Player
