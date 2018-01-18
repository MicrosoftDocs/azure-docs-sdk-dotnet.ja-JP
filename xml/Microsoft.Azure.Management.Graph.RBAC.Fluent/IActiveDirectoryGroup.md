<Type Name="IActiveDirectoryGroup" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryGroup">
  <TypeSignature Language="C#" Value="public interface IActiveDirectoryGroup : Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryObject, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.ActiveDirectoryGroup.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActiveDirectoryGroup implements class Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryObject, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.ActiveDirectoryGroup.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryGroup" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActiveDirectoryGroup&#xA;Implements IActiveDirectoryObject, IBeta, IHasId, IHasInner(Of ADGroupInner), IHasManager(Of GraphRbacManager), IHasName, IIndexable, IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IActiveDirectoryGroup = interface&#xA;    interface IBeta&#xA;    interface IActiveDirectoryObject&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasManager&lt;GraphRbacManager&gt;&#xA;    interface IHasInner&lt;ADGroupInner&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryObject</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.ActiveDirectoryGroup.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="3b067-101">Azure AD グループの変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="3b067-101">An immutable client-side representation of an Azure AD group.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="3b067-102">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="3b067-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="ListMembers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryObject&gt; ListMembers ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryObject&gt; ListMembers() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryGroup.ListMembers" />
      <MemberSignature Language="VB.NET" Value="Public Function ListMembers () As IEnumerable(Of IActiveDirectoryObject)" />
      <MemberSignature Language="F#" Value="abstract member ListMembers : unit -&gt; seq&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryObject&gt;" Usage="iActiveDirectoryGroup.ListMembers " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMembersAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryObject&gt;&gt; ListMembersAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryObject&gt;&gt; ListMembersAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryGroup.ListMembersAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMembersAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryObject&gt;&gt;" Usage="iActiveDirectoryGroup.ListMembersAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mail">
      <MemberSignature Language="C#" Value="public string Mail { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Mail" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryGroup.Mail" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Mail As String" />
      <MemberSignature Language="F#" Value="member this.Mail : string" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryGroup.Mail" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b067-103">フィールドのメールを取得します。</span><span class="sxs-lookup"><span data-stu-id="3b067-103">Gets mail field.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityEnabled">
      <MemberSignature Language="C#" Value="public bool SecurityEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SecurityEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryGroup.SecurityEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecurityEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.SecurityEnabled : bool" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryGroup.SecurityEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b067-104">セキュリティが有効なフィールドを取得します。</span><span class="sxs-lookup"><span data-stu-id="3b067-104">Gets security enabled field.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>