<Type Name="AppServiceEnvironmentsOperationsExtensions" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AppServiceEnvironmentsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AppServiceEnvironmentsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AppServiceEnvironmentsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AppServiceEnvironmentsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            AppServiceEnvironmentsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner hostingEnvironmentEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner hostingEnvironmentEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, name, hostingEnvironmentEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__36))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="hostingEnvironmentEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="hostingEnvironmentEnvelope">
            App Service 環境の構成の詳細。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成または App Service 環境を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            作成または App Service 環境を更新します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateMultiRolePoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; BeginCreateOrUpdateMultiRolePoolAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner multiRolePoolEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; BeginCreateOrUpdateMultiRolePoolAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner multiRolePoolEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateMultiRolePoolAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateMultiRolePoolAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateMultiRolePoolAsync (operations, resourceGroupName, name, multiRolePoolEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginCreateOrUpdateMultiRolePoolAsync&gt;d__38))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="multiRolePoolEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="multiRolePoolEnvelope">
            マルチロール プールのプロパティです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成またはマルチロール プールを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            作成またはマルチロール プールを更新します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWorkerPoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; BeginCreateOrUpdateWorkerPoolAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner workerPoolEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; BeginCreateOrUpdateWorkerPoolAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner workerPoolEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateWorkerPoolAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWorkerPoolAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateWorkerPoolAsync (operations, resourceGroupName, name, workerPoolName, workerPoolEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginCreateOrUpdateWorkerPoolAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="workerPoolEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="workerPoolName">
            ワーカー プールの名前です。
            </param>
        <param name="workerPoolEnvelope">
            ワーカー プールのプロパティです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成またはワーカー プールを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            作成またはワーカー プールを更新します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; forceDelete = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; forceDelete, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, name, forceDelete, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="forceDelete" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="forceDelete">
            指定&lt;コード&gt;true&lt;/code&gt;を App Service 環境には、リソースが含まれている場合でも強制的に削除します。 既定値は&lt;コード&gt;false&lt;/code&gt;です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service 環境を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境を削除します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResumeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginResumeAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginResumeAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginResumeAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResumeAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginResumeAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginResumeAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service 環境を再開します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境を再開します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResumeNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginResumeNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginResumeNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginResumeNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResumeNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginResumeNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginResumeNextAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            App Service 環境を再開します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境を再開します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSuspendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginSuspendAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginSuspendAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginSuspendAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginSuspendAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginSuspendAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginSuspendAsync&gt;d__40))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service 環境を中断します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境を中断します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSuspendNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginSuspendNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginSuspendNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginSuspendNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginSuspendNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginSuspendNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginSuspendNextAsync&gt;d__66))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            App Service 環境を中断します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境を中断します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner hostingEnvironmentEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner hostingEnvironmentEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, name, hostingEnvironmentEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="hostingEnvironmentEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="hostingEnvironmentEnvelope">
            App Service 環境の構成の詳細。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成または App Service 環境を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            作成または App Service 環境を更新します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateMultiRolePoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; CreateOrUpdateMultiRolePoolAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner multiRolePoolEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; CreateOrUpdateMultiRolePoolAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner multiRolePoolEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateMultiRolePoolAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateMultiRolePoolAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateMultiRolePoolAsync (operations, resourceGroupName, name, multiRolePoolEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;CreateOrUpdateMultiRolePoolAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="multiRolePoolEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="multiRolePoolEnvelope">
            マルチロール プールのプロパティです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成またはマルチロール プールを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            作成またはマルチロール プールを更新します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWorkerPoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; CreateOrUpdateWorkerPoolAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner workerPoolEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; CreateOrUpdateWorkerPoolAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner workerPoolEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateWorkerPoolAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWorkerPoolAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateWorkerPoolAsync (operations, resourceGroupName, name, workerPoolName, workerPoolEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;CreateOrUpdateWorkerPoolAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="workerPoolEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="workerPoolName">
            ワーカー プールの名前です。
            </param>
        <param name="workerPoolEnvelope">
            ワーカー プールのプロパティです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成またはワーカー プールを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            作成またはワーカー プールを更新します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; forceDelete = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; forceDelete, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.DeleteAsync (operations, resourceGroupName, name, forceDelete, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;DeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="forceDelete" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="forceDelete">
            指定&lt;コード&gt;true&lt;/code&gt;を App Service 環境には、リソースが含まれている場合でも強制的に削除します。 既定値は&lt;コード&gt;false&lt;/code&gt;です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service 環境を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境を削除します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt; GetAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt; GetAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service 環境のプロパティを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境のプロパティを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDiagnosticsItemAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt; GetDiagnosticsItemAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string diagnosticsName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt; GetDiagnosticsItemAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string diagnosticsName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetDiagnosticsItemAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDiagnosticsItemAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetDiagnosticsItemAsync (operations, resourceGroupName, name, diagnosticsName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;GetDiagnosticsItemAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="diagnosticsName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="diagnosticsName">
            診断の項目の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service 環境の診断の項目を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境の診断の項目を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMultiRolePoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; GetMultiRolePoolAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; GetMultiRolePoolAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetMultiRolePoolAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetMultiRolePoolAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetMultiRolePoolAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;GetMultiRolePoolAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            マルチロール プールのプロパティを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            マルチロール プールのプロパティを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetWorkerPoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; GetWorkerPoolAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; GetWorkerPoolAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetWorkerPoolAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetWorkerPoolAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetWorkerPoolAsync (operations, resourceGroupName, name, workerPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;GetWorkerPoolAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="workerPoolName">
            ワーカー プールの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ワーカー プールのプロパティを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ワーカー プールのプロパティを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAppServicePlansAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListAppServicePlansAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListAppServicePlansAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListAppServicePlansAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAppServicePlansAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListAppServicePlansAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListAppServicePlansAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service Environment ですべての App Service プランを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service Environment ですべての App Service プランを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAppServicePlansNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListAppServicePlansNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListAppServicePlansNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListAppServicePlansNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAppServicePlansNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListAppServicePlansNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListAppServicePlansNextAsync&gt;d__54))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            App Service Environment ですべての App Service プランを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service Environment ですべての App Service プランを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            App Service 環境のすべてのサブスクリプションを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境のすべてのサブスクリプションを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループ内のすべての App Service 環境を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            リソース グループ内のすべての App Service 環境を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            リソース グループ内のすべての App Service 環境を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            リソース グループ内のすべての App Service 環境を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCapacitiesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt; ListCapacitiesAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt; ListCapacitiesAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListCapacitiesAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCapacitiesAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListCapacitiesAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListCapacitiesAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service 環境に使用される、使用可能なおよび合計ワーカー容量を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境に使用される、使用可能なおよび合計ワーカー容量を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCapacitiesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt; ListCapacitiesNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt; ListCapacitiesNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListCapacitiesNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCapacitiesNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListCapacitiesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListCapacitiesNextAsync&gt;d__44))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            App Service 環境に使用される、使用可能なおよび合計ワーカー容量を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境に使用される、使用可能なおよび合計ワーカー容量を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDiagnosticsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt;&gt; ListDiagnosticsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt;&gt; ListDiagnosticsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListDiagnosticsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListDiagnosticsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListDiagnosticsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListDiagnosticsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service 環境の診断情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境の診断情報を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.MetricDefinitionInner&gt; ListMetricDefinitionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.MetricDefinitionInner&gt; ListMetricDefinitionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMetricDefinitionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinitionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.MetricDefinitionInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMetricDefinitionsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMetricDefinitionsAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.MetricDefinitionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service 環境のグローバルのメトリックの定義を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境のグローバルのメトリックの定義を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; details = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; details, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMetricsAsync (operations, resourceGroupName, name, details, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMetricsAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="details">
            指定&lt;コード&gt;true&lt;/code&gt;にインスタンスの詳細を含めます。 既定値は&lt;コード&gt;false&lt;/code&gt;です。
            </param>
        <param name="filter">
            使用状況/メトリックのみ、フィルターで指定されたを返します。 フィルターは、odata 構文に準拠します。 例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2') と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [時間 |分 |1 日]'。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service 環境のグローバルのメトリックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境のグローバルのメトリックを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMetricsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMetricsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMetricsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMetricsNextAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            App Service 環境のグローバルのメトリックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境のグローバルのメトリックを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRoleMetricDefinitionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRoleMetricDefinitionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricDefinitionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleMetricDefinitionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricDefinitionsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleMetricDefinitionsAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricDefinitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRoleMetricDefinitionsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRoleMetricDefinitionsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricDefinitionsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleMetricDefinitionsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricDefinitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleMetricDefinitionsNextAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRoleMetricsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string startTime = null, string endTime = null, string timeGrain = null, Nullable&lt;bool&gt; details = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRoleMetricsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string startTime, string endTime, string timeGrain, valuetype System.Nullable`1&lt;bool&gt; details, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleMetricsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricsAsync (operations, resourceGroupName, name, startTime, endTime, timeGrain, details, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleMetricsAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="timeGrain" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="startTime">
            メトリックのクエリの時間を開始しています。
            </param>
        <param name="endTime">
            メトリックのクエリの終了時刻です。
            </param>
        <param name="timeGrain">
            メトリックのクエリの時間粒度。
            </param>
        <param name="details">
            指定&lt;コード&gt;true&lt;/code&gt;にインスタンスの詳細を含めます。 既定値は&lt;コード&gt;false&lt;/code&gt;です。
            </param>
        <param name="filter">
            使用状況/メトリックのみ、フィルターで指定されたを返します。 フィルターは、odata 構文に準拠します。 例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2') と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [時間 |分 |1 日]'。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service 環境のマルチロール プールのメトリックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境のマルチロール プールのメトリックを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRoleMetricsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRoleMetricsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleMetricsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleMetricsNextAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            App Service 環境のマルチロール プールのメトリックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境のマルチロール プールのメトリックを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRolePoolInstanceMetricDefinitionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string instance, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRolePoolInstanceMetricDefinitionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string instance, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricDefinitionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolInstanceMetricDefinitionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricDefinitionsAsync (operations, resourceGroupName, name, instance, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolInstanceMetricDefinitionsAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="instance">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricDefinitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRolePoolInstanceMetricDefinitionsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRolePoolInstanceMetricDefinitionsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricDefinitionsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolInstanceMetricDefinitionsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricDefinitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolInstanceMetricDefinitionsNextAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRolePoolInstanceMetricsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string instance, Nullable&lt;bool&gt; details = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRolePoolInstanceMetricsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string instance, valuetype System.Nullable`1&lt;bool&gt; details, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolInstanceMetricsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricsAsync (operations, resourceGroupName, name, instance, details, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolInstanceMetricsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="instance">
            マルチロール プール内のインスタンスの名前です。
            </param>
        <param name="details">
            指定&lt;コード&gt;true&lt;/code&gt;にインスタンスの詳細を含めます。 既定値は&lt;コード&gt;false&lt;/code&gt;です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service 環境のマルチロール プールの特定のインスタンスのメトリックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境のマルチロール プールの特定のインスタンスのメトリックを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRolePoolInstanceMetricsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRolePoolInstanceMetricsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolInstanceMetricsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolInstanceMetricsNextAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            App Service 環境のマルチロール プールの特定のインスタンスのメトリックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境のマルチロール プールの特定のインスタンスのメトリックを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListMultiRolePoolsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListMultiRolePoolsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolsAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            マルチロールすべてのプールを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            マルチロールすべてのプールを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolSkusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListMultiRolePoolSkusAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListMultiRolePoolSkusAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolSkusAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolSkusAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolSkusAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolSkusAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            マルチロール プールを拡張するためには、利用可能な Sku を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            マルチロール プールを拡張するためには、利用可能な Sku を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolSkusNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListMultiRolePoolSkusNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListMultiRolePoolSkusNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolSkusNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolSkusNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolSkusNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolSkusNextAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            マルチロール プールを拡張するためには、利用可能な Sku を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            マルチロール プールを拡張するためには、利用可能な Sku を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListMultiRolePoolsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListMultiRolePoolsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolsNextAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            マルチロールすべてのプールを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            マルチロールすべてのプールを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListMultiRoleUsagesAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListMultiRoleUsagesAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleUsagesAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleUsagesAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleUsagesAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleUsagesAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleUsagesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListMultiRoleUsagesNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListMultiRoleUsagesNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleUsagesNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleUsagesNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleUsagesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleUsagesNextAsync&gt;d__52))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListNextAsync&gt;d__42))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            App Service 環境のすべてのサブスクリプションを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境のすべてのサブスクリプションを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOperationsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner&gt;&gt; ListOperationsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner&gt;&gt; ListOperationsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListOperationsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOperationsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListOperationsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListOperationsAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service 環境の現在実行されているすべての操作を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境の現在実行されているすべての操作を一覧表示します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt; ListUsagesAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt; ListUsagesAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListUsagesAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListUsagesAsync (operations, resourceGroupName, name, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListUsagesAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="filter">
            使用状況/メトリックのみ、フィルターで指定されたを返します。 フィルターは、odata 構文に準拠します。 例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2') と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [時間 |分 |1 日]'。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service 環境のグローバルの使用状況メトリックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境のグローバルの使用状況メトリックを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt; ListUsagesNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt; ListUsagesNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListUsagesNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListUsagesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListUsagesNextAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            App Service 環境のグローバルの使用状況メトリックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境のグローバルの使用状況メトリックを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVipsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner&gt; ListVipsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner&gt; ListVipsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListVipsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVipsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListVipsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListVipsAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service 環境に割り当てる IP アドレスを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境に割り当てる IP アドレスを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ListWebAppsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string propertiesToInclude = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ListWebAppsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string propertiesToInclude, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebAppsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebAppsAsync (operations, resourceGroupName, name, propertiesToInclude, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebAppsAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="propertiesToInclude" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="propertiesToInclude">
            コンマ区切りリストに含めるアプリのプロパティです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service Environment ですべてのアプリを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service Environment ですべてのアプリを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ListWebAppsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ListWebAppsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebAppsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebAppsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebAppsNextAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            App Service Environment ですべてのアプリを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service Environment ですべてのアプリを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWebWorkerMetricDefinitionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWebWorkerMetricDefinitionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricDefinitionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerMetricDefinitionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricDefinitionsAsync (operations, resourceGroupName, name, workerPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerMetricDefinitionsAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="workerPoolName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricDefinitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWebWorkerMetricDefinitionsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWebWorkerMetricDefinitionsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricDefinitionsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerMetricDefinitionsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricDefinitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerMetricDefinitionsNextAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWebWorkerMetricsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, Nullable&lt;bool&gt; details = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWebWorkerMetricsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Nullable`1&lt;bool&gt; details, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerMetricsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricsAsync (operations, resourceGroupName, name, workerPoolName, details, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerMetricsAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="workerPoolName">
            ワーカー プールの名前
            </param>
        <param name="details">
            指定&lt;コード&gt;true&lt;/code&gt;にインスタンスの詳細を含めます。 既定値は&lt;コード&gt;false&lt;/code&gt;です。
            </param>
        <param name="filter">
            使用状況/メトリックのみ、フィルターで指定されたを返します。 フィルターは、odata 構文に準拠します。 例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2') と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [時間 |分 |1 日]'。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            AppServiceEnvironment (App Service Environment) のワーカー プールのメトリックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            AppServiceEnvironment (App Service Environment) のワーカー プールのメトリックを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWebWorkerMetricsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWebWorkerMetricsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerMetricsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerMetricsNextAsync&gt;d__62))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            AppServiceEnvironment (App Service Environment) のワーカー プールのメトリックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            AppServiceEnvironment (App Service Environment) のワーカー プールのメトリックを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListWebWorkerUsagesAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListWebWorkerUsagesAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerUsagesAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerUsagesAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerUsagesAsync (operations, resourceGroupName, name, workerPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerUsagesAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="workerPoolName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerUsagesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListWebWorkerUsagesNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListWebWorkerUsagesNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerUsagesNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerUsagesNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerUsagesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerUsagesNextAsync&gt;d__64))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWorkerPoolInstanceMetricDefinitionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, string instance, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWorkerPoolInstanceMetricDefinitionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, string instance, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricDefinitionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolInstanceMetricDefinitionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricDefinitionsAsync (operations, resourceGroupName, name, workerPoolName, instance, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolInstanceMetricDefinitionsAsync&gt;d__30))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="workerPoolName">To be added.</param>
        <param name="instance">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricDefinitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWorkerPoolInstanceMetricDefinitionsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWorkerPoolInstanceMetricDefinitionsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricDefinitionsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolInstanceMetricDefinitionsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricDefinitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolInstanceMetricDefinitionsNextAsync&gt;d__59))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWorkerPoolInstanceMetricsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, string instance, Nullable&lt;bool&gt; details = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWorkerPoolInstanceMetricsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, string instance, valuetype System.Nullable`1&lt;bool&gt; details, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolInstanceMetricsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricsAsync (operations, resourceGroupName, name, workerPoolName, instance, details, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolInstanceMetricsAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="workerPoolName">
            ワーカー プールの名前です。
            </param>
        <param name="instance">
            ワーカー プールのインスタンスの名前。
            </param>
        <param name="details">
            指定&lt;コード&gt;true&lt;/code&gt;にインスタンスの詳細を含めます。 既定値は&lt;コード&gt;false&lt;/code&gt;です。
            </param>
        <param name="filter">
            使用状況/メトリックのみ、フィルターで指定されたを返します。 フィルターは、odata 構文に準拠します。 例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2') と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [時間 |分 |1 日]'。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service 環境のワーカー プールの特定のインスタンスのメトリックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境のワーカー プールの特定のインスタンスのメトリックを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWorkerPoolInstanceMetricsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWorkerPoolInstanceMetricsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolInstanceMetricsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolInstanceMetricsNextAsync&gt;d__60))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            App Service 環境のワーカー プールの特定のインスタンスのメトリックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境のワーカー プールの特定のインスタンスのメトリックを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListWorkerPoolsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListWorkerPoolsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolsAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service 環境のすべてのワーカー プールを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境のすべてのワーカー プールを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolSkusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListWorkerPoolSkusAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListWorkerPoolSkusAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolSkusAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolSkusAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolSkusAsync (operations, resourceGroupName, name, workerPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolSkusAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="workerPoolName">
            ワーカー プールの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ワーカー プールを拡張するためには、利用可能な Sku を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ワーカー プールを拡張するためには、利用可能な Sku を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolSkusNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListWorkerPoolSkusNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListWorkerPoolSkusNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolSkusNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolSkusNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolSkusNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolSkusNextAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            ワーカー プールを拡張するためには、利用可能な Sku を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ワーカー プールを拡張するためには、利用可能な Sku を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListWorkerPoolsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListWorkerPoolsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolsNextAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            App Service 環境のすべてのワーカー プールを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境のすべてのワーカー プールを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebootAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RebootAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RebootAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.RebootAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RebootAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.RebootAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;RebootAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service 環境のすべてのマシンを再起動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境のすべてのマシンを再起動します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ResumeAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ResumeAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ResumeAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResumeAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ResumeAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ResumeAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service 環境を再開します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境を再開します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ResumeNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ResumeNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ResumeNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResumeNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ResumeNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ResumeNextAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            App Service 環境を再開します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境を再開します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; SuspendAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; SuspendAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.SuspendAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SuspendAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.SuspendAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;SuspendAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service 環境の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service 環境を中断します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境を中断します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; SuspendNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; SuspendNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.SuspendNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SuspendNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.SuspendNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;SuspendNextAsync&gt;d__56))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            App Service 環境を中断します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service 環境を中断します。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>