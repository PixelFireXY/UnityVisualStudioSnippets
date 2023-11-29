## UnityVisualStudioSnippets

Snippets to make programmer's life easier, designed for Unity

### Shortcuts

| Snippet name  | Snippet shortcut | Snippet code | Description |
| ------------- | ------------- | ------------- | ------------- |
| Brackeys wrap  | brackets  | { code }  | Code snipped to wrap code between brackeys. |
| Debug Log  | dl  | Debug.Log($"string");  | String to print at console. |
| Debug Log Brackeys  | dlb  | Debug.Log($"{value}");  | Value from a variable or something else to print at console. |
| Debug Log Warning  | dlw  | Debug.LogWarning($"string");  | String to print warning at console |
| Debug Log Warning Brackeys  | dlwb  | Debug.LogWarning($"{variable}");  | Value from a variable or something else to print warning at console. |
| Debug Log Error  | dle  | Debug.LogError($"string");  | String to print error at console |
| Debug Log Error Brackeys  | dleb  | Debug.LogError($"{variable}");  | Value from a variable or something else to print error at console. |
| header | header | [Header("string")]  | Create the header attribute. |
| Horizontal Rule  | hr  | /******************** HorizontalRule ********************/  | Handy divider to organize your code. |
| Inspector Button  | ib  | [InspectorButton(nameof(MethodName) <br />[SerializeField] private bool methodName;  | [InspectorButton dependent] Create an InspectorButton attribute. |
| Private Method  | private  | private void MethodName()<br /> { &nbsp;}  | Empty private void method. |
| Private Return Method  | privater  | private void MethodName()<br /> { &nbsp;return null; }  | Empty private method with return type. |
| Private Method  | public  | private void MethodName()<br /> { &nbsp;}  | Empty public void method. |
| Private Return Method  | publicr  | private void MethodName()<br /> { &nbsp;return null; }  | Empty public method with return type. |
| Private Method  | protected  | private void MethodName()<br /> { &nbsp;}  | Empty protected void method. |
| Private Return Method  | protectedr  | private void MethodName()<br /> { &nbsp;return null; }  | Empty protected method with return type. |
| Property with lambda  | propl  | public object PropertyName { get => fieldName; set => fieldName = value; }<br />[SerializeField] private object fieldName = new object();   | Property with private field |
| SerializeField property  | sf  | [SerializeField] private object fieldName;  | Unity SerializeField attribute. |
| SerializeField property new  | sfnew  | [SerializeField] private object fieldName = new object();  | Unity SerializeField attribute with new costructor. |
| SerializeField property null  | sfnull  | [SerializeField] private object fieldName = null;  | Unity SerializeField attribute initialized null. |
| Tooltip property | tooltip  | [Tooltip("string")]  | Tooltip Unity attribute. |
| Coroutine Method  | ienumerator  | private IEnumerator CoroutineName()<br /> { &nbsp;yield return null; }  | Create a Ienumerator method. |
| StartCoroutine  | sc  | StartCoroutine(CoroutineName());  | StartCoroutine call. |
| Yield null  | yrn  | yield return null;  | Null return for coroutines. |
| Yield WaitForSeconds | yrnwfs  | yield return new WaitForSeconds(value);  | WaitForSeconds return for coroutines. |
| Yield WaitUntil | yrnwu  | yield return new WaitUntil(() => value);  | WaitUntil return for coroutines. |
| Yield WaitWhile | yrnww  | yield return new WaitWhile(() => value);  | WaitWhile return for coroutines. |
