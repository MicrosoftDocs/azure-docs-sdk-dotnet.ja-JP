<Type Name="IWithRouteTable&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithRouteTable&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithRouteTable&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRouteTable`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithRouteTable`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRouteTable(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithRouteTable&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">親の型。</typeparam>
    <summary>
            サブネットに関連付けるルート テーブルの指定を許可するサブネットの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingRouteTable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithExistingRouteTable (Microsoft.Azure.Management.Network.Fluent.IRouteTable routeTable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithExistingRouteTable(class Microsoft.Azure.Management.Network.Fluent.IRouteTable routeTable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithRouteTable`1.WithExistingRouteTable(Microsoft.Azure.Management.Network.Fluent.IRouteTable)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingRouteTable (routeTable As IRouteTable) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingRouteTable : Microsoft.Azure.Management.Network.Fluent.IRouteTable -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithRouteTable.WithExistingRouteTable routeTable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="routeTable" Type="Microsoft.Azure.Management.Network.Fluent.IRouteTable" />
      </Parameters>
      <Docs>
        <param name="routeTable">関連付ける既存のルート テーブル。</param>
        <summary>
            サブネットに関連付ける既存のルート テーブルを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingRouteTable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithExistingRouteTable (string resourceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithExistingRouteTable(string resourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithRouteTable`1.WithExistingRouteTable(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingRouteTable (resourceId As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingRouteTable : string -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithRouteTable.WithExistingRouteTable resourceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceId">既存のルート テーブルのリソース ID です。</param>
        <summary>
            サブネットに関連付ける既存のルート テーブルを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>