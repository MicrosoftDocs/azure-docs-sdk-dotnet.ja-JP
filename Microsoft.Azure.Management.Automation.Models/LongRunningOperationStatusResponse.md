<Type Name="LongRunningOperationStatusResponse" FullName="Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse">
  <TypeSignature Language="C#" Value="public class LongRunningOperationStatusResponse : Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LongRunningOperationStatusResponse extends Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class LongRunningOperationStatusResponse&#xA;Inherits AzureOperationResponse" />
  <TypeSignature Language="F#" Value="type LongRunningOperationStatusResponse = class&#xA;    inherit AzureOperationResponse" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.AzureOperationResponse</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            応答本文には、かどうかそれが成功したは、処理中、または失敗を示すが、指定した非同期操作の状態が含まれています。 この状態は、Get Operation Status 操作自体に対して返される HTTP ステータス コードと異なることに注意してください。  非同期操作が成功した場合、応答本文には、成功した要求の HTTP ステータス コードが含まれています。  非同期操作に失敗した場合、応答本文は、失敗した要求の HTTP ステータス コードが含まれています、失敗に関するエラー情報も含まれます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LongRunningOperationStatusResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            LongRunningOperationStatusResponse クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.ErrorDetails Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse/ErrorDetails Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As LongRunningOperationStatusResponse.ErrorDetails" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.ErrorDetails with get, set" Usage="Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse+ErrorDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 非同期操作に失敗した場合、応答本文は、失敗した要求の HTTP ステータス コードが含まれています、失敗に関するエラー情報も含まれます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpStatusCode">
      <MemberSignature Language="C#" Value="public System.Net.HttpStatusCode HttpStatusCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Net.HttpStatusCode HttpStatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.HttpStatusCode" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpStatusCode As HttpStatusCode" />
      <MemberSignature Language="F#" Value="member this.HttpStatusCode : System.Net.HttpStatusCode with get, set" Usage="Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.HttpStatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpStatusCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 非同期要求の HTTP ステータス コード。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 非同期要求の要求 ID です。 この値は、非同期要求の x ms 要求 id の応答ヘッダーで返されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.OperationStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.OperationStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As OperationStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.OperationStatus with get, set" Usage="Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.OperationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 非同期要求の状態です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>