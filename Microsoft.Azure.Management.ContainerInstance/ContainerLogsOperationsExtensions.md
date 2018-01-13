<Type Name="ContainerLogsOperationsExtensions" FullName="Microsoft.Azure.Management.ContainerInstance.ContainerLogsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ContainerLogsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ContainerLogsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.ContainerLogsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ContainerLogsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ContainerLogsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ContainerLogsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerInstance.Models.Logs List (this Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations operations, string resourceGroupName, string containerGroupName, string containerName, Nullable&lt;int&gt; tail = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerInstance.Models.Logs List(class Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations operations, string resourceGroupName, string containerGroupName, string containerName, valuetype System.Nullable`1&lt;int32&gt; tail) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.ContainerLogsOperationsExtensions.List(Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations,System.String,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IContainerLogsOperations, resourceGroupName As String, containerGroupName As String, containerName As String, Optional tail As Nullable(Of Integer) = null) As Logs" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations * string * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.ContainerInstance.Models.Logs" Usage="Microsoft.Azure.Management.ContainerInstance.ContainerLogsOperationsExtensions.List (operations, resourceGroupName, containerGroupName, containerName, tail)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerInstance.Models.Logs</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerGroupName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="tail" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="containerGroupName">
            コンテナーのグループの名前。
            </param>
        <param name="containerName">
            コンテナーのインスタンスの名前。
            </param>
        <param name="tail">
            コンテナーのインスタンスのログの末尾が示される行の数。 指定しない場合、使用可能なすべてのログは、最大 4 mb のとおりです。
            </param>
        <summary>
            インスタンスの指定されたコンテナーのログを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ログは、指定されたリソース グループおよびコンテナーのグループで指定されたコンテナー インスタンスを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerInstance.Models.Logs&gt; ListAsync (this Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations operations, string resourceGroupName, string containerGroupName, string containerName, Nullable&lt;int&gt; tail = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.Logs&gt; ListAsync(class Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations operations, string resourceGroupName, string containerGroupName, string containerName, valuetype System.Nullable`1&lt;int32&gt; tail, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.ContainerLogsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations,System.String,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations * string * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerInstance.Models.Logs&gt;" Usage="Microsoft.Azure.Management.ContainerInstance.ContainerLogsOperationsExtensions.ListAsync (operations, resourceGroupName, containerGroupName, containerName, tail, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerInstance.ContainerLogsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerInstance.Models.Logs&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerGroupName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="tail" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="containerGroupName">
            コンテナーのグループの名前。
            </param>
        <param name="containerName">
            コンテナーのインスタンスの名前。
            </param>
        <param name="tail">
            コンテナーのインスタンスのログの末尾が示される行の数。 指定しない場合、使用可能なすべてのログは、最大 4 mb のとおりです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            インスタンスの指定されたコンテナーのログを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ログは、指定されたリソース グループおよびコンテナーのグループで指定されたコンテナー インスタンスを取得します。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>