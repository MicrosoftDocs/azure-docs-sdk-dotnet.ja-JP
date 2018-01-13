<Type Name="DataContainerOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataContainerOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataContainerOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataContainerOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataContainerOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            これは、StorSimple のオブジェクトを管理する rest ベースの API
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreating">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginCreating (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginCreating(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginCreating(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreating : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginCreating (operations, deviceId, containerDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="containerDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。
            </param>
        <param name="deviceId">
            必須。 デバイス id
            </param>
        <param name="containerDetails">
            必須。 パラメーターは、作成するボリューム コンテナーの開始操作に指定します。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>
            作成するボリューム コンテナーの開始操作は、新しいボリューム コンテナーを作成します。
            </summary>
        <returns>
            これは、非同期呼び出しは、すべてのタスク応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreatingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginCreatingAsync(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreatingAsync : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginCreatingAsync (operations, deviceId, containerDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="containerDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。
            </param>
        <param name="deviceId">
            必須。 デバイス id
            </param>
        <param name="containerDetails">
            必須。 パラメーターは、作成するボリューム コンテナーの開始操作に指定します。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>
            作成するボリューム コンテナーの開始操作は、新しいボリューム コンテナーを作成します。
            </summary>
        <returns>
            これは、非同期呼び出しは、すべてのタスク応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleting">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginDeleting (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginDeleting(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginDeleting(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeleting : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginDeleting (operations, deviceId, dataContainerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。
            </param>
        <param name="deviceId">
            必須。 デバイス id
            </param>
        <param name="dataContainerId">
            必須。 削除する必要があるデータ コンテナーの id
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>
            削除するボリューム コンテナーの開始操作には、指定したボリューム コンテナーが削除されます。
            </summary>
        <returns>
            これは、非同期呼び出しは、すべてのタスク応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeletingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginDeletingAsync(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeletingAsync : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginDeletingAsync (operations, deviceId, dataContainerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。
            </param>
        <param name="deviceId">
            必須。 デバイス id
            </param>
        <param name="dataContainerId">
            必須。 削除する必要があるデータ コンテナーの id
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>
            削除するボリューム コンテナーの開始操作には、指定したボリューム コンテナーが削除されます。
            </summary>
        <returns>
            これは、非同期呼び出しは、すべてのタスク応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.Create(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.Create (operations, deviceId, containerDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="containerDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。
            </param>
        <param name="deviceId">
            必須。 デバイス id
            </param>
        <param name="containerDetails">
            必須。 パラメーターは、ボリューム コンテナーの作成操作に指定します。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.CreateAsync(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.CreateAsync (operations, deviceId, containerDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="containerDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。
            </param>
        <param name="deviceId">
            必須。 デバイス id
            </param>
        <param name="containerDetails">
            必須。 パラメーターは、ボリューム コンテナーの作成操作に指定します。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.Delete(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.Delete (operations, deviceId, dataContainerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。
            </param>
        <param name="deviceId">
            必須。 デバイス id
            </param>
        <param name="dataContainerId">
            必須。 削除する必要があるデータ コンテナーの id
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.DeleteAsync(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.DeleteAsync (operations, deviceId, dataContainerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。
            </param>
        <param name="deviceId">
            必須。 デバイス id
            </param>
        <param name="dataContainerId">
            必須。 削除する必要があるデータ コンテナーの id
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse Get (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerName, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse Get(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerName, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.Get(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.Get (operations, deviceId, dataContainerName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。
            </param>
        <param name="deviceId">
            省略可能。
            </param>
        <param name="dataContainerName">
            省略可能。
            </param>
        <param name="customRequestHeaders">
            省略可能。
            </param>
        <summary>To be added.</summary>
        <returns>
            データ コンテナーの get 応答モデルです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse&gt; GetAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerName, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerName, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.GetAsync (operations, deviceId, dataContainerName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。
            </param>
        <param name="deviceId">
            省略可能。
            </param>
        <param name="dataContainerName">
            省略可能。
            </param>
        <param name="customRequestHeaders">
            省略可能。
            </param>
        <summary>To be added.</summary>
        <returns>
            データ コンテナーの get 応答モデルです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse List (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse List(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.List(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.List (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。
            </param>
        <param name="deviceId">
            省略可能。
            </param>
        <param name="customRequestHeaders">
            省略可能。
            </param>
        <summary>To be added.</summary>
        <returns>
            データ コンテナーの一覧について応答モデルです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse&gt; ListAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse&gt; ListAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.ListAsync(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.ListAsync (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。
            </param>
        <param name="deviceId">
            省略可能。
            </param>
        <param name="customRequestHeaders">
            省略可能。
            </param>
        <summary>To be added.</summary>
        <returns>
            データ コンテナーの一覧について応答モデルです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>