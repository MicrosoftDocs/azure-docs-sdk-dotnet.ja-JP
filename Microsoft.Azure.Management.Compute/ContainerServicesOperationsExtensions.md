<Type Name="ContainerServicesOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ContainerServicesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ContainerServicesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ContainerServicesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ContainerServicesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ContainerServicesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.ContainerService BeginCreateOrUpdate (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, Microsoft.Azure.Management.Compute.Models.ContainerService parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.ContainerService BeginCreateOrUpdate(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, class Microsoft.Azure.Management.Compute.Models.ContainerService parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.ContainerService)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IContainerServicesOperations, resourceGroupName As String, containerServiceName As String, parameters As ContainerService) As ContainerService" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * Microsoft.Azure.Management.Compute.Models.ContainerService -&gt; Microsoft.Azure.Management.Compute.Models.ContainerService" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, containerServiceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ContainerService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.ContainerService" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="containerServiceName">
            指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。
            </param>
        <param name="parameters">
            作成または更新コンテナー サービス操作に渡されるパラメーターです。
            </param>
        <summary>
            作成するか、コンテナー サービスを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            作成または、orchestrator、マスター、およびエージェントの指定の構成を持つコンテナー サービスを更新します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, Microsoft.Azure.Management.Compute.Models.ContainerService parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, class Microsoft.Azure.Management.Compute.Models.ContainerService parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.ContainerService,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * Microsoft.Azure.Management.Compute.Models.ContainerService * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, containerServiceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.ContainerService" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="containerServiceName">
            指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。
            </param>
        <param name="parameters">
            作成または更新コンテナー サービス操作に渡されるパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、コンテナー サービスを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            作成または、orchestrator、マスター、およびエージェントの指定の構成を持つコンテナー サービスを更新します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IContainerServicesOperations, resourceGroupName As String, containerServiceName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginDelete (operations, resourceGroupName, containerServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="containerServiceName">
            指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。
            </param>
        <summary>
            指定されたコンテナー サービスを削除します。
            </summary>
        <remarks>
            指定したサブスクリプションとリソース グループ内の指定されたコンテナー サービスを削除します。 操作では、ストレージ アカウント、Vm を含む、コンテナー サービスの作成の一部として作成されたその他のリソースは削除されませんし、可用性セットします。 コンテナー サービスで作成されたその他のすべてのリソースは、同じリソース グループの一部であるし、個別に削除することができます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, containerServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="containerServiceName">
            指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたコンテナー サービスを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定したサブスクリプションとリソース グループ内の指定されたコンテナー サービスを削除します。 操作では、ストレージ アカウント、Vm を含む、コンテナー サービスの作成の一部として作成されたその他のリソースは削除されませんし、可用性セットします。 コンテナー サービスで作成されたその他のすべてのリソースは、同じリソース グループの一部であるし、個別に削除することができます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.ContainerService CreateOrUpdate (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, Microsoft.Azure.Management.Compute.Models.ContainerService parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.ContainerService CreateOrUpdate(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, class Microsoft.Azure.Management.Compute.Models.ContainerService parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.ContainerService)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IContainerServicesOperations, resourceGroupName As String, containerServiceName As String, parameters As ContainerService) As ContainerService" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * Microsoft.Azure.Management.Compute.Models.ContainerService -&gt; Microsoft.Azure.Management.Compute.Models.ContainerService" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, containerServiceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ContainerService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.ContainerService" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="containerServiceName">
            指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。
            </param>
        <param name="parameters">
            作成または更新コンテナー サービス操作に渡されるパラメーターです。
            </param>
        <summary>
            作成するか、コンテナー サービスを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            作成または、orchestrator、マスター、およびエージェントの指定の構成を持つコンテナー サービスを更新します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, Microsoft.Azure.Management.Compute.Models.ContainerService parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, class Microsoft.Azure.Management.Compute.Models.ContainerService parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.ContainerService,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * Microsoft.Azure.Management.Compute.Models.ContainerService * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, containerServiceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.ContainerService" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="containerServiceName">
            指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。
            </param>
        <param name="parameters">
            作成または更新コンテナー サービス操作に渡されるパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、コンテナー サービスを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            作成または、orchestrator、マスター、およびエージェントの指定の構成を持つコンテナー サービスを更新します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.Delete(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IContainerServicesOperations, resourceGroupName As String, containerServiceName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.Delete (operations, resourceGroupName, containerServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="containerServiceName">
            指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。
            </param>
        <summary>
            指定されたコンテナー サービスを削除します。
            </summary>
        <remarks>
            指定したサブスクリプションとリソース グループ内の指定されたコンテナー サービスを削除します。 操作では、ストレージ アカウント、Vm を含む、コンテナー サービスの作成の一部として作成されたその他のリソースは削除されませんし、可用性セットします。 コンテナー サービスで作成されたその他のすべてのリソースは、同じリソース グループの一部であるし、個別に削除することができます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.DeleteAsync (operations, resourceGroupName, containerServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="containerServiceName">
            指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたコンテナー サービスを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定したサブスクリプションとリソース グループ内の指定されたコンテナー サービスを削除します。 操作では、ストレージ アカウント、Vm を含む、コンテナー サービスの作成の一部として作成されたその他のリソースは削除されませんし、可用性セットします。 コンテナー サービスで作成されたその他のすべてのリソースは、同じリソース グループの一部であるし、個別に削除することができます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.ContainerService Get (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.ContainerService Get(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.Get(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IContainerServicesOperations, resourceGroupName As String, containerServiceName As String) As ContainerService" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.ContainerService" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.Get (operations, resourceGroupName, containerServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ContainerService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="containerServiceName">
            指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。
            </param>
        <summary>
            指定されたコンテナー サービスのプロパティを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定したサブスクリプションとリソース グループで指定されたコンテナー サービスのプロパティを取得します。 操作は、状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; GetAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; GetAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.GetAsync (operations, resourceGroupName, containerServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="containerServiceName">
            指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたコンテナー サービスのプロパティを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定したサブスクリプションとリソース グループで指定されたコンテナー サービスのプロパティを取得します。 操作は、状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; List (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; List(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.List(Microsoft.Azure.Management.Compute.IContainerServicesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IContainerServicesOperations) As IPage(Of ContainerService)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Compute.IContainerServicesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <summary>
            指定されたサブスクリプションのコンテナー サービスの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定されたサブスクリプションのコンテナー サービスの一覧を取得します。 操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたサブスクリプションのコンテナー サービスの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定されたサブスクリプションのコンテナー サービスの一覧を取得します。 操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; ListByResourceGroup (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; ListByResourceGroup(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IContainerServicesOperations, resourceGroupName As String) As IPage(Of ContainerService)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <summary>
            指定されたリソース グループ内のコンテナー サービスの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定したサブスクリプションとリソース グループ内のコンテナー サービスの一覧を取得します。 操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたリソース グループ内のコンテナー サービスの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定したサブスクリプションとリソース グループ内のコンテナー サービスの一覧を取得します。 操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IContainerServicesOperations, nextPageLink As String) As IPage(Of ContainerService)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <summary>
            指定されたリソース グループ内のコンテナー サービスの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定したサブスクリプションとリソース グループ内のコンテナー サービスの一覧を取得します。 操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたリソース グループ内のコンテナー サービスの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定したサブスクリプションとリソース グループ内のコンテナー サービスの一覧を取得します。 操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; ListNext (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; ListNext(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListNext(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IContainerServicesOperations, nextPageLink As String) As IPage(Of ContainerService)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <summary>
            指定されたサブスクリプションのコンテナー サービスの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定されたサブスクリプションのコンテナー サービスの一覧を取得します。 操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;ListNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたサブスクリプションのコンテナー サービスの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定されたサブスクリプションのコンテナー サービスの一覧を取得します。 操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>