<Type Name="ISupportsGettingByResourceGroup&lt;T&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByResourceGroup&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface ISupportsGettingByResourceGroup&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISupportsGettingByResourceGroup`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByResourceGroup`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISupportsGettingByResourceGroup(Of T)" />
  <TypeSignature Language="F#" Value="type ISupportsGettingByResourceGroup&lt;'T&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetByResourceGroup">
      <MemberSignature Language="C#" Value="public T GetByResourceGroup (string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T GetByResourceGroup(string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByResourceGroup`1.GetByResourceGroup(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetByResourceGroup (resourceGroupName As String, name As String) As T" />
      <MemberSignature Language="F#" Value="abstract member GetByResourceGroup : string * string -&gt; 'T" Usage="iSupportsGettingByResourceGroup.GetByResourceGroup (resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">リソースがリソース グループの名前</param>
        <param name="name">リソースの名前。 (注、これは、ID ではありません)</param>
        <summary>
            リソース名とそのリソース グループの名前に基づいて Azure からのリソースに関する情報を取得します。
            </summary>
        <returns>リソースの変更できない表現</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetByResourceGroupAsync (string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; GetByResourceGroupAsync(string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByResourceGroup`1.GetByResourceGroupAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetByResourceGroupAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iSupportsGettingByResourceGroup.GetByResourceGroupAsync (resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">リソースがリソース グループの名前</param>
        <param name="name">リソースの名前。 (注、これは、ID ではありません)</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            リソース名とそのリソース グループの名前に基づいて Azure からのリソースに関する情報を取得します。
            </summary>
        <returns>リソースの変更できない表現</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>