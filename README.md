# PersistentCacheHelper

How to use
1- Add file to youre project
2- To load use PersistentCache.TryLoad<T>("key");
3- To save use PersistentCache.Save<T>("key",data);
4- Done!
  
  The script uses binary serialization, supports the preservation of all standard types.
To work correctly, the persisted class must have the attribute [Serializable]
