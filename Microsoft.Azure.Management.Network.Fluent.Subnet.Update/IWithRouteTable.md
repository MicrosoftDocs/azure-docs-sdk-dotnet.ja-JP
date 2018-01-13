<Type Name="IWithRouteTable" FullName="Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithRouteTable">
  <TypeSignature Language="C#" Value="public interface IWithRouteTable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRouteTable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithRouteTable" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRouteTable" />
  <TypeSignature Language="F#" Value="type IWithRouteTable = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            サブネットのステージでは、更新可能であり、サブネットに関連付けるルート テーブルを指定するのにまたは、既存の関連付けを削除します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingRouteTable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithExistingRouteTable (Microsoft.Azure.Management.Network.Fluent.IRouteTable routeTable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithExistingRouteTable(class Microsoft.Azure.Management.Network.Fluent.IRouteTable routeTable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithRouteTable.WithExistingRouteTable(Microsoft.Azure.Management.Network.Fluent.IRouteTable)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingRouteTable (routeTable As IRouteTable) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingRouteTable : Microsoft.Azure.Management.Network.Fluent.IRouteTable -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate" Usage="iWithRouteTable.WithExistingRouteTable routeTable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate</ReturnType>
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
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingRouteTable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithExistingRouteTable (string resourceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithExistingRouteTable(string resourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithRouteTable.WithExistingRouteTable(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingRouteTable (resourceId As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingRouteTable : string -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate" Usage="iWithRouteTable.WithExistingRouteTable resourceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate</ReturnType>
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
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutRouteTable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithoutRouteTable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithoutRouteTable() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithRouteTable.WithoutRouteTable" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutRouteTable () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutRouteTable : unit -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate" Usage="iWithRouteTable.WithoutRouteTable " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            存在する場合は、ルート テーブルとの関連付けを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>