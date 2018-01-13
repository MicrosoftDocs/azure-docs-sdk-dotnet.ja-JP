<Type Name="DeviceDetailsOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DeviceDetailsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DeviceDetailsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DeviceDetailsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DeviceDetailsOperationsExtensions = class" />
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
    <Member MemberName="BeginUpdateDeviceDetails">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginUpdateDeviceDetails (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginUpdateDeviceDetails(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.BeginUpdateDeviceDetails(Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateDeviceDetails : Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.BeginUpdateDeviceDetails (operations, deviceDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations" RefType="this" />
        <Parameter Name="deviceDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations への参照。
            </param>
        <param name="deviceDetails">
            必須。 更新された DeviceDetails です。 対応するデバイス Id が含まれています
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>
            DeviceDetails で指定されたデバイスの詳細を更新するためのタスクを開始します。 返されるタスクの情報を使用して完了タスクを追跡することができますし、
            </summary>
        <returns>
            これは、非同期呼び出しは、すべてのタスク応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateDeviceDetailsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdateDeviceDetailsAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdateDeviceDetailsAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.BeginUpdateDeviceDetailsAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateDeviceDetailsAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.BeginUpdateDeviceDetailsAsync (operations, deviceDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations" RefType="this" />
        <Parameter Name="deviceDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations への参照。
            </param>
        <param name="deviceDetails">
            必須。 更新された DeviceDetails です。 対応するデバイス Id が含まれています
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>
            DeviceDetails で指定されたデバイスの詳細を更新するためのタスクを開始します。 返されるタスクの情報を使用して完了タスクを追跡することができますし、
            </summary>
        <returns>
            これは、非同期呼び出しは、すべてのタスク応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse Get (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse Get(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.Get(Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.Get (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            デバイスの詳細の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse&gt; GetAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.GetAsync (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            デバイスの詳細の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceDetails">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateDeviceDetails (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateDeviceDetails(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.UpdateDeviceDetails(Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateDeviceDetails : Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.UpdateDeviceDetails (operations, deviceDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations" RefType="this" />
        <Parameter Name="deviceDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations への参照。
            </param>
        <param name="deviceDetails">
            必須。 更新された DeviceDetails です。 対応するデバイス Id が含まれています
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>
            DeviceDetails で指定されたデバイスの詳細を更新します。
            </summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceDetailsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDeviceDetailsAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDeviceDetailsAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.UpdateDeviceDetailsAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateDeviceDetailsAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.UpdateDeviceDetailsAsync (operations, deviceDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations" RefType="this" />
        <Parameter Name="deviceDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations への参照。
            </param>
        <param name="deviceDetails">
            必須。 更新された DeviceDetails です。 対応するデバイス Id が含まれています
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>
            DeviceDetails で指定されたデバイスの詳細を更新します。
            </summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>