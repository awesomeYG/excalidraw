# Excalidraw

**Excalidraw** 基于开源项目 Excalidraw ，引入了中文手写体（沐瑶随心手写体）

## 使用方法

1. 引入 css 文件 
import "@excalidraw/excalidraw/index.css"

2. 在 next 项目中使用 
useEffect(() => { import('@excalidraw/excalidraw').then((comp: any) => setExcalidraw(comp.Excalidraw) ); }, []);
