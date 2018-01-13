<Type Name="ContainerOperationsExtensions" FullName="Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ContainerOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ContainerOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ContainerOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ContainerOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse List (this Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters parameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse List(class Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters parameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.List(Microsoft.Azure.Management.BackupServices.IContainerOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.BackupServices.IContainerOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse" Usage="Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.List (operations, resourceGroupName, resourceName, parameters, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.BackupServices.IContainerOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。
            </param>
        <param name="resourceName">
            必須。
            </param>
        <param name="parameters">
            省略可能。 コンテナーのクエリのパラメーターです。
            </param>
        <param name="customRequestHeaders">
            省略可能。 ヘッダーのパラメーターを要求します。
            </param>
        <summary>
            指定されたクエリのフィルター文字列に基づくすべてのコンテナーの一覧を取得します。
            </summary>
        <returns>
            CSMContainerListOperationResponse の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse&gt; ListAsync (this Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters parameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse&gt; ListAsync(class Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters parameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.ListAsync(Microsoft.Azure.Management.BackupServices.IContainerOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.BackupServices.IContainerOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.ListAsync (operations, resourceGroupName, resourceName, parameters, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.BackupServices.IContainerOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。
            </param>
        <param name="resourceName">
            必須。
            </param>
        <param name="parameters">
            省略可能。 コンテナーのクエリのパラメーターです。
            </param>
        <param name="customRequestHeaders">
            省略可能。 ヘッダーのパラメーターを要求します。
            </param>
        <summary>
            指定されたクエリのフィルター文字列に基づくすべてのコンテナーの一覧を取得します。
            </summary>
        <returns>
            CSMContainerListOperationResponse の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse Refresh (this Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse Refresh(class Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.Refresh(Microsoft.Azure.Management.BackupServices.IContainerOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Refresh : Microsoft.Azure.Management.BackupServices.IContainerOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.Refresh (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.BackupServices.IContainerOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。
            </param>
        <param name="resourceName">
            必須。
            </param>
        <param name="customRequestHeaders">
            省略可能。 ヘッダーのパラメーターを要求します。
            </param>
        <summary>
            この検出をトリガーします。
            </summary>
        <returns>
            操作の応答の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; RefreshAsync (this Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; RefreshAsync(class Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.RefreshAsync(Microsoft.Azure.Management.BackupServices.IContainerOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member RefreshAsync : Microsoft.Azure.Management.BackupServices.IContainerOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.RefreshAsync (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.BackupServices.IContainerOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。
            </param>
        <param name="resourceName">
            必須。
            </param>
        <param name="customRequestHeaders">
            省略可能。 ヘッダーのパラメーターを要求します。
            </param>
        <summary>
            この検出をトリガーします。
            </summary>
        <returns>
            操作の応答の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Register">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse Register (this Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, string containerName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse Register(class Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, string containerName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.Register(Microsoft.Azure.Management.BackupServices.IContainerOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Register : Microsoft.Azure.Management.BackupServices.IContainerOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.Register (operations, resourceGroupName, resourceName, containerName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.BackupServices.IContainerOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。
            </param>
        <param name="resourceName">
            必須。
            </param>
        <param name="containerName">
            必須。 登録するコンテナーです。
            </param>
        <param name="customRequestHeaders">
            省略可能。 ヘッダーのパラメーターを要求します。
            </param>
        <summary>
            コンテナーを登録します。
            </summary>
        <returns>
            操作の応答の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; RegisterAsync (this Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, string containerName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; RegisterAsync(class Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, string containerName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.RegisterAsync(Microsoft.Azure.Management.BackupServices.IContainerOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member RegisterAsync : Microsoft.Azure.Management.BackupServices.IContainerOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.RegisterAsync (operations, resourceGroupName, resourceName, containerName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.BackupServices.IContainerOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。
            </param>
        <param name="resourceName">
            必須。
            </param>
        <param name="containerName">
            必須。 登録するコンテナーです。
            </param>
        <param name="customRequestHeaders">
            省略可能。 ヘッダーのパラメーターを要求します。
            </param>
        <summary>
            コンテナーを登録します。
            </summary>
        <returns>
            操作の応答の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unregister">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse Unregister (this Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, string containerName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse Unregister(class Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, string containerName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.Unregister(Microsoft.Azure.Management.BackupServices.IContainerOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Unregister : Microsoft.Azure.Management.BackupServices.IContainerOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.Unregister (operations, resourceGroupName, resourceName, containerName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.BackupServices.IContainerOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。
            </param>
        <param name="resourceName">
            必須。
            </param>
        <param name="containerName">
            必須。 登録を解除するコンテナーです。
            </param>
        <param name="customRequestHeaders">
            必須。 ヘッダーのパラメーターを要求します。
            </param>
        <summary>
            コンテナーの登録を解除します。
            </summary>
        <returns>
            操作の応答の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UnregisterAsync (this Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, string containerName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UnregisterAsync(class Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, string containerName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.UnregisterAsync(Microsoft.Azure.Management.BackupServices.IContainerOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UnregisterAsync : Microsoft.Azure.Management.BackupServices.IContainerOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.UnregisterAsync (operations, resourceGroupName, resourceName, containerName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.BackupServices.IContainerOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。
            </param>
        <param name="resourceName">
            必須。
            </param>
        <param name="containerName">
            必須。 登録を解除するコンテナーです。
            </param>
        <param name="customRequestHeaders">
            必須。 ヘッダーのパラメーターを要求します。
            </param>
        <summary>
            コンテナーの登録を解除します。
            </summary>
        <returns>
            操作の応答の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>