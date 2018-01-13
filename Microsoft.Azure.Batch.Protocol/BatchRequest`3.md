<Type Name="BatchRequest&lt;TBody,TOptions,TResponse&gt;" FullName="Microsoft.Azure.Batch.Protocol.BatchRequest&lt;TBody,TOptions,TResponse&gt;">
  <TypeSignature Language="C#" Value="public class BatchRequest&lt;TBody,TOptions,TResponse&gt; : Microsoft.Azure.Batch.Protocol.BatchRequestBase&lt;TOptions,TResponse&gt; where TOptions : IOptionsnew() where TResponse : IAzureOperationResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchRequest`3&lt;TBody, .ctor (class Microsoft.Azure.Batch.Protocol.Models.IOptions) TOptions, (class Microsoft.Rest.Azure.IAzureOperationResponse) TResponse&gt; extends Microsoft.Azure.Batch.Protocol.BatchRequestBase`2&lt;!TOptions, !TResponse&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequest`3" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchRequest(Of TBody, TOptions, TResponse)&#xA;Inherits BatchRequestBase(Of TOptions, TResponse)" />
  <TypeSignature Language="F#" Value="type BatchRequest&lt;'Body, 'Options, 'Response (requires 'Options :&gt; IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; IAzureOperationResponse)&gt; = class&#xA;    inherit BatchRequestBase&lt;'Options, 'Response (requires 'Options :&gt; IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; IAzureOperationResponse)&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TBody" />
    <TypeParameter Name="TOptions">
      <Constraints>
        <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
        <InterfaceName>Microsoft.Azure.Batch.Protocol.Models.IOptions</InterfaceName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="TResponse">
      <Constraints>
        <InterfaceName>Microsoft.Rest.Azure.IAzureOperationResponse</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequestBase&lt;TOptions,TResponse&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TOptions">TOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">TResponse</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TBody">要求に関連付けられている本文パラメーターの型。</typeparam>
    <typeparam name="TOptions">要求に関連付けられている、要求本文の外側のパラメーターの型が渡されます。</typeparam>
    <typeparam name="TResponse">要求から予想される応答の種類。</typeparam>
    <summary>
            型の要求本体を持つ特定の呼び出しに必要な情報を表す<typeparamref name="TBody" />バッチをサービスの REST API です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient restClient, TBody parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient restClient, !TBody parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequest`3.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,`0,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequest&lt;'Body, 'Options, 'Response (requires 'Options :&gt; Microsoft.Azure.Batch.Protocol.Models.IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt; : Microsoft.Azure.Batch.Protocol.BatchServiceClient * 'Body * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequest&lt;'Body, 'Options, 'Response (requires 'Options :&gt; Microsoft.Azure.Batch.Protocol.Models.IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt;" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequest&lt;'Body, 'Options, 'Response (requires 'Options :&gt; Microsoft.Azure.Batch.Protocol.Models.IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt; (restClient, parameters, cancellationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="restClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
        <Parameter Name="parameters" Type="TBody" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="restClient">REST クライアントが使用します。</param>
        <param name="parameters">使用するパラメーター。</param>
        <param name="cancellationToken">使用するキャンセル トークン。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequest`3" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public TBody Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TBody Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.BatchRequest`3.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As TBody" />
      <MemberSignature Language="F#" Value="member this.Parameters : 'Body with get, set" Usage="Microsoft.Azure.Batch.Protocol.BatchRequest&lt;'Body, 'Options, 'Response (requires 'Options :&gt; Microsoft.Azure.Batch.Protocol.Models.IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt;.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TBody</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または REST API の要求本文で渡されるパラメーターを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>