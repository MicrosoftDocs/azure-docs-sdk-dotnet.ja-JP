<Type Name="AzureAsyncOperationResult" FullName="Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult">
  <TypeSignature Language="C#" Value="public class AzureAsyncOperationResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureAsyncOperationResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureAsyncOperationResult" />
  <TypeSignature Language="F#" Value="type AzureAsyncOperationResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            応答本文には、かどうかそれが成功したが進行中、または失敗を示すが、指定した非同期操作の状態が含まれています。 この状態は、Get Operation Status 操作自体に対して返される HTTP ステータス コードと異なることに注意してください。 非同期操作が成功した場合、応答本文には、成功した要求の HTTP ステータス コードが含まれています。 非同期操作に失敗した場合、応答本文には、失敗した要求とエラーに関する情報、エラーの HTTP ステータス コードが含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureAsyncOperationResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AzureAsyncOperationResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureAsyncOperationResult (string status = null, Microsoft.Azure.Management.Network.Fluent.Models.Error error = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string status, class Microsoft.Azure.Management.Network.Fluent.Models.Error error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult.#ctor(System.String,Microsoft.Azure.Management.Network.Fluent.Models.Error)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult : string * Microsoft.Azure.Management.Network.Fluent.Models.Error -&gt; Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult (status, error)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="error" Type="Microsoft.Azure.Management.Network.Fluent.Models.Error" />
      </Parameters>
      <Docs>
        <param name="status">Azure の非同期操作の状態です。 使用可能な値が: '処理中'、'成功' および '失敗' です。 使用可能な値が含まれます: '処理中'、'成功', '失敗'</param>
        <param name="error">To be added.</param>
        <summary>
            AzureAsyncOperationResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.Error Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.Error Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As Error" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Management.Network.Fluent.Models.Error with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.Error</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure の非同期操作の状態を設定します。 使用可能な値が: '処理中'、'成功' および '失敗' です。 使用可能な値が含まれます: '処理中'、'成功', '失敗'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>