<Type Name="DesiredPropertyUpdateCallback" FullName="Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback">
  <TypeSignature Language="C#" Value="public delegate System.Threading.Tasks.Task DesiredPropertyUpdateCallback(TwinCollection desiredProperties, object userContext);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed DesiredPropertyUpdateCallback extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Function DesiredPropertyUpdateCallback(desiredProperties As TwinCollection, userContext As Object) As Task " />
  <TypeSignature Language="F#" Value="type DesiredPropertyUpdateCallback = delegate of TwinCollection * obj -&gt; Task" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="desiredProperties" Type="Microsoft.Azure.Devices.Shared.TwinCollection" />
    <Parameter Name="userContext" Type="System.Object" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Threading.Tasks.Task</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="desiredProperties"><span data-ttu-id="ace00-101">サービスから受信した更新プログラムに含まれていたプロパティ</span><span class="sxs-lookup"><span data-stu-id="ace00-101">Properties that were contained in the update that was received from the service</span></span></param>
    <param name="userContext"><span data-ttu-id="ace00-102">コールバックの登録時に渡されるコンテキスト オブジェクト</span><span class="sxs-lookup"><span data-stu-id="ace00-102">Context object passed in when the callback was registered</span></span></param>
    <summary>
            <span data-ttu-id="ace00-103">目的のプロパティの更新プログラムのコールバック デリゲート。</span><span class="sxs-lookup"><span data-stu-id="ace00-103">Delegate for desired property update callbacks.</span></span>  <span data-ttu-id="ace00-104">これは、パッチ、サービスから受信するたびに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="ace00-104">This will be called every time we receive a PATCH from the service.</span></span>
            </summary>
    <returns>To be added.</returns>
    <remarks>To be added.</remarks>
  </Docs>
</Type>