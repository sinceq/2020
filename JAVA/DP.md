练习

一、

```
public abstract Class Character {
    WeaponBehavior weaponBehavior;
    public Charavter(){}
    public void setWeaponBehavio(WeaponBehavior weaponBehavior)
    {
        this.weaponBehavior = weaponBehavior;
    }
    public void fight()
    {
    		sout("Use " + this.weaponBehavior + " fight!");
    }
}
```

```
public interface WeaponBehavior{
    public void useWeapon()
    {
    }
}
```



二、Ω