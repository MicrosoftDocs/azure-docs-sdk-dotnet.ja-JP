<Type Name="RequestReplacementInterceptor" FullName="Microsoft.Azure.Batch.Protocol.RequestReplacementInterceptor">
  <TypeSignature Language="C#" Value="public class RequestReplacementInterceptor : Microsoft.Azure.Batch.BatchClientBehavior" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RequestReplacementInterceptor extends Microsoft.Azure.Batch.BatchClientBehavior" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.RequestReplacementInterceptor" />
  <TypeSignature Language="VB.NET" Value="Public Class RequestReplacementInterceptor&#xA;Inherits BatchClientBehavior" />
  <TypeSignature Language="F#" Value="type RequestReplacementInterceptor = class&#xA;    inherit BatchClientBehavior" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.BatchClientBehavior</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            派生クラスでは、検査、置換、または、BatchRequest を変更できます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestReplacementInterceptor ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.RequestReplacementInterceptor.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            RequestReplacementInterceptor の新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestReplacementInterceptor (Microsoft.Azure.Batch.Protocol.BatchRequestReplacementInterceptHandler replacementInterceptor);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchRequestReplacementInterceptHandler replacementInterceptor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.RequestReplacementInterceptor.#ctor(Microsoft.Azure.Batch.Protocol.BatchRequestReplacementInterceptHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (replacementInterceptor As BatchRequestReplacementInterceptHandler)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.RequestReplacementInterceptor : Microsoft.Azure.Batch.Protocol.BatchRequestReplacementInterceptHandler -&gt; Microsoft.Azure.Batch.Protocol.RequestReplacementInterceptor" Usage="new Microsoft.Azure.Batch.Protocol.RequestReplacementInterceptor replacementInterceptor" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="replacementInterceptor" Type="Microsoft.Azure.Batch.Protocol.BatchRequestReplacementInterceptHandler" />
      </Parameters>
      <Docs>
        <param name="replacementInterceptor"></param>
        <summary>
            RequestReplacementInterceptor の新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplacementInterceptHandler">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.BatchRequestReplacementInterceptHandler ReplacementInterceptHandler { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.BatchRequestReplacementInterceptHandler ReplacementInterceptHandler" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.RequestReplacementInterceptor.ReplacementInterceptHandler" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplacementInterceptHandler As BatchRequestReplacementInterceptHandler" />
      <MemberSignature Language="F#" Value="member this.ReplacementInterceptHandler : Microsoft.Azure.Batch.Protocol.BatchRequestReplacementInterceptHandler with get, set" Usage="Microsoft.Azure.Batch.Protocol.RequestReplacementInterceptor.ReplacementInterceptHandler" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.BatchRequestReplacementInterceptHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定する直前に呼び出されるメソッド、<see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" />を実行します。
            要求を検査、交換、変更または無視します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>