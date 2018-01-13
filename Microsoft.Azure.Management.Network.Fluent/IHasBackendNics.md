<Type Name="IHasBackendNics" FullName="Microsoft.Azure.Management.Network.Fluent.IHasBackendNics">
  <TypeSignature Language="C#" Value="public interface IHasBackendNics" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IHasBackendNics" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.IHasBackendNics" />
  <TypeSignature Language="VB.NET" Value="Public Interface IHasBackendNics" />
  <TypeSignature Language="F#" Value="type IHasBackendNics = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="95e71-101">関連付けられているネットワーク インターフェイスの一覧を参照するバックエンドの機能を表すインターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="95e71-101">An interface representing a backend's ability to reference a list of associated network interfaces.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BackendNicIPConfigurationNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,string&gt; BackendNicIPConfigurationNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, string&gt; BackendNicIPConfigurationNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IHasBackendNics.BackendNicIPConfigurationNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackendNicIPConfigurationNames As IReadOnlyDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.BackendNicIPConfigurationNames : System.Collections.Generic.IReadOnlyDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.IHasBackendNics.BackendNicIPConfigurationNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95e71-102">NIC のリソース id によってインデックス付けされた、このバックエンドに割り当てられているネットワーク インターフェイスの IP 構成の名前のマップを取得します。</span><span class="sxs-lookup"><span data-stu-id="95e71-102">Gets a map of names of the IP configurations of network interfaces assigned to this backend, indexed by their NIC's resource id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>