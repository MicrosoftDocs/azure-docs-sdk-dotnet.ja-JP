<Type Name="ICNameRecordSet" FullName="Microsoft.Azure.Management.Dns.Fluent.ICNameRecordSet">
  <TypeSignature Language="C#" Value="public interface ICNameRecordSet : Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet,Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICNameRecordSet implements class Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource`2&lt;class Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet, class Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.ICNameRecordSet" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICNameRecordSet&#xA;Implements IChildResource(Of IDnsZone), IDnsRecordSet, IExternalChildResource(Of IDnsRecordSet, IDnsZone), IHasInner(Of RecordSetInner), IHasParent(Of IDnsZone), IRefreshable(Of IDnsRecordSet)" />
  <TypeSignature Language="F#" Value="type ICNameRecordSet = interface&#xA;    interface IDnsRecordSet&#xA;    interface IExternalChildResource&lt;IDnsRecordSet, IDnsZone&gt;&#xA;    interface IChildResource&lt;IDnsZone&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;IDnsZone&gt;&#xA;    interface IRefreshable&lt;IDnsRecordSet&gt;&#xA;    interface IHasInner&lt;RecordSetInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet,Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="28783-101">CNAME (正規名) レコードの変更できないクライアント側表現は、Azure DNS ゾーンで設定します。</span><span class="sxs-lookup"><span data-stu-id="28783-101">An immutable client-side representation of a CNAME (canonical name) record set in Azure DNS Zone.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CanonicalName">
      <MemberSignature Language="C#" Value="public string CanonicalName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CanonicalName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.ICNameRecordSet.CanonicalName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CanonicalName As String" />
      <MemberSignature Language="F#" Value="member this.CanonicalName : string" Usage="Microsoft.Azure.Management.Dns.Fluent.ICNameRecordSet.CanonicalName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="28783-102">このレコード セット内の CName レコードの正規名 (せずに末尾のドット) を取得します。</span><span class="sxs-lookup"><span data-stu-id="28783-102">Gets the canonical name (without a terminating dot) of CName record in this record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>