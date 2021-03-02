# Personal information

**Name:** Daniil Yahiptsau\
**Address:** Belarus, Minsk\
**Phone:** +375-44-546-54-74\
**Date of birth:** 4 September 2002\
**Age:** 18\
**GitHub** <https://github.com/Dauniusha/rsschool-cv>

# About me

I am a hard worker when it comes to what I am fond of. And I am good at math.\
I want to try myself as a web developer.

# Skills

- с++ \*6kyu [codewars](https://www.codewars.com/users/Dauniusha)\*
- basic level JS CCS and HTML
- intermediate level of English
- pre-intermediate level of French

## example of my code on c++

```
//This function opens squares with zeros in the game "Minesweeper"
void NullCheker(vector<vector <Square>> &square, const int size, const int x, const int y)
{
	square[x][y].SetStatus(common);
	for (int i = x - 1; i < x + 2; i++)
	{
		if ((i < 0) || (i > size - 1))
			continue;
		for (int j = y - 1; j < y + 2; j++)
		{
			if ((j < 0) || (j > size - 1))
				continue;
			else
				if (square[i][j].GetStatus() == null)
					NullCheker(square, size, i, j);
				else
					square[i][j].SquareOpening();
		}
	}
}
```

# Work experience

None
