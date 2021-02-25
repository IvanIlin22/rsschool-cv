# Ivan Ilin

## Contacts

* Telegram: @gradus22
* Email: geniusmov@yandex.ru

### About me

I'm an aspiring  Junior Developer, who potentially wants to become a Fullstack Developer.

Right now I don't have much of experience in the field, but I've already finished some freelance projects.I love to learn, that's why I'm currently studying online to achive my goal of becoming a pro.

#### Skills:

- Java
- Golang
- Python
- C/C++
- Postgres
- MySql
- GIT
- HTML
- Unit Testing 

#### Code example:

```
#include "libft.h"

static int	ft_size(long n)
{
	int		size;
	int		znak;

	znak = 0;
	size = 1;
	if (n < 0)
	{
		znak = 1;
		n *= -1;
	}
	while (n >= 10)
	{
		n /= 10;
		size += 1;
	}
	size = size + znak;
	return (size);
}

char		*ft_itoa(int n)
{
	char	*str;
	int		size;
	int		i;
	long	nb;

	nb = n;
	size = ft_size(nb);
	str = (char*)malloc(sizeof(char) * (size + 1));
	if (str == NULL)
		return (NULL);
	if (nb < 0)
	{
		str[0] = '-';
		nb *= -1;
	}
	i = size - 1;
	while (nb >= 10)
	{
		str[i] = nb % 10 + '0';
		nb /= 10;
		i--;
	}
	str[i] = nb % 10 + '0';
	str[size] = '\0';
	return (str);
}
```

#### Education

2013 - 2019 National Research University MPEI

21 school

#### English

Intermediate(B1)
