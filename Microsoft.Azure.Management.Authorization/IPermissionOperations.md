<Type Name="IPermissionOperations" FullName="Microsoft.Azure.Management.Authorization.IPermissionOperations">
  <TypeSignature Language="C#" Value="public interface IPermissionOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPermissionOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Authorization.IPermissionOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPermissionOperations" />
  <TypeSignature Language="F#" Value="type IPermissionOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            リソースまたはリソース グループの権限 (詳細については http://TBD を参照してください) を取得します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListForResourceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt; ListForResourceAsync (string resourceGroupName, Microsoft.Azure.ResourceIdentity identity, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt; ListForResourceAsync(string resourceGroupName, class Microsoft.Azure.ResourceIdentity identity, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IPermissionOperations.ListForResourceAsync(System.String,Microsoft.Azure.ResourceIdentity,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForResourceAsync : string * Microsoft.Azure.ResourceIdentity * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt;" Usage="iPermissionOperations.ListForResourceAsync (resourceGroupName, identity, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="identity" Type="Microsoft.Azure.ResourceIdentity" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="identity">
            リソース
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソースのアクセス許可を取得します。
            </summary>
        <returns>
            権限に関する情報。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt; ListForResourceGroupAsync (string resourceGroupName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt; ListForResourceGroupAsync(string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IPermissionOperations.ListForResourceGroupAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForResourceGroupAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt;" Usage="iPermissionOperations.ListForResourceGroupAsync (resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            アクセス許可を取得するリソース グループの名前です。名前は大文字小文字を区別します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループのアクセス許可を取得します。
            </summary>
        <returns>
            権限に関する情報。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>