<Type Name="BatchSharedKeyCredential" FullName="Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential">
  <TypeSignature Language="C#" Value="public class BatchSharedKeyCredential : Microsoft.Rest.ServiceClientCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchSharedKeyCredential extends Microsoft.Rest.ServiceClientCredentials" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchSharedKeyCredential&#xA;Inherits ServiceClientCredentials" />
  <TypeSignature Language="F#" Value="type BatchSharedKeyCredential = class&#xA;    inherit ServiceClientCredentials" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClientCredentials</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Azure Batch アカウントのキーの資格情報を共有します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchSharedKeyCredential (string accountName, string keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, string keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, keyValue As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential : string * string -&gt; Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential" Usage="new Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential (accountName, keyValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName">Batch アカウントの名前。</param>
        <param name="keyValue">Base64 でエンコードされた文字列として、Batch アカウントのアクセス キー。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string" Usage="Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Batch アカウント名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyValue">
      <MemberSignature Language="C#" Value="public string KeyValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential.KeyValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyValue As String" />
      <MemberSignature Language="F#" Value="member this.KeyValue : string" Usage="Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential.KeyValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Base64 でエンコードされた文字列として、アカウント アクセス キーを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessHttpRequestAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task ProcessHttpRequestAsync (System.Net.Http.HttpRequestMessage httpRequest, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task ProcessHttpRequestAsync(class System.Net.Http.HttpRequestMessage httpRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential.ProcessHttpRequestAsync(System.Net.Http.HttpRequestMessage,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.ProcessHttpRequestAsync : System.Net.Http.HttpRequestMessage * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="batchSharedKeyCredential.ProcessHttpRequestAsync (httpRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="httpRequest" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="httpRequest">HTTP 要求</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />要求します。</param>
        <summary>
            現在の資格情報を持つ記号、HTTP 要求。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />非同期署名操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>