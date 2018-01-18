<Type Name="ShouldOverwriteCallback" FullName="Microsoft.WindowsAzure.Storage.DataMovement.ShouldOverwriteCallback">
  <TypeSignature Language="C#" Value="public delegate bool ShouldOverwriteCallback(object source, object destination);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ShouldOverwriteCallback extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.ShouldOverwriteCallback" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Function ShouldOverwriteCallback(source As Object, destination As Object) As Boolean " />
  <TypeSignature Language="F#" Value="type ShouldOverwriteCallback = delegate of obj * obj -&gt; bool" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="source" Type="System.Object" />
    <Parameter Name="destination" Type="System.Object" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Boolean</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="source"><span data-ttu-id="6f6af-101">変換先を上書きに使用するソースのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="6f6af-101">Instance of source used to overwrite the destination.</span></span></param>
    <param name="destination"><span data-ttu-id="6f6af-102">上書きする移行先のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="6f6af-102">Instance of destination to be overwritten.</span></span></param>
    <summary>
            <span data-ttu-id="6f6af-103">既存の変換先を上書きするかどうかに呼び出されるコールバック。</span><span class="sxs-lookup"><span data-stu-id="6f6af-103">Callback invoked to tell whether to overwrite an existing destination.</span></span>
            </summary>
    <returns><span data-ttu-id="6f6af-104">ファイルを上書きする場合は true。それ以外の場合は false。</span><span class="sxs-lookup"><span data-stu-id="6f6af-104">True if the file should be overwritten; otherwise false.</span></span></returns>
    <remarks>To be added.</remarks>
  </Docs>
</Type>