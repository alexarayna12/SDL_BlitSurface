# SDL_BlitSurface
pOldBitmap = _SDL_CreateRGBSurfaceFrom($Scan0, $iWidth, $iHeight, 32, $iWidth * 4, 0, 0, 0, 0) $pNewSurface = _SDL_CreateRGBSurface($_SDL_SWSURFACE, $iWidth, $iHeight, 32, 0, 0, 0, 0)   ;If you set 0 for $iRmask, $iGmask, $iBmask, $iAmask it will be set to a default value _SDL_BlitSurface($pOldBitmap, 0, $pNewSurface, 0)
