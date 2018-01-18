<Type Name="RequestInterceptor" FullName="Microsoft.Azure.Batch.Protocol.RequestInterceptor">
  <TypeSignature Language="C#" Value="public class RequestInterceptor : Microsoft.Azure.Batch.Protocol.RequestReplacementInterceptor" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RequestInterceptor extends Microsoft.Azure.Batch.Protocol.RequestReplacementInterceptor" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.RequestInterceptor" />
  <TypeSignature Language="VB.NET" Value="Public Class RequestInterceptor&#xA;Inherits RequestReplacementInterceptor" />
  <TypeSignature Language="F#" Value="type RequestInterceptor = class&#xA;    inherit RequestReplacementInterceptor" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.RequestReplacementInterceptor</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5146f-101">このクラスは、検査、変更、または無視するインターセプターをできるように、<see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" />です。</span><span class="sxs-lookup"><span data-stu-id="5146f-101">This class enables an interceptor to inspect, modify or ignore a <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestInterceptor ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.RequestInterceptor.#ctor" />
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
            <span data-ttu-id="5146f-102">RequestInterceptor の新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5146f-102">Initializes a new instance of RequestInterceptor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestInterceptor (Microsoft.Azure.Batch.Protocol.BatchRequestModificationInterceptHandler interceptor);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchRequestModificationInterceptHandler interceptor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.RequestInterceptor.#ctor(Microsoft.Azure.Batch.Protocol.BatchRequestModificationInterceptHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (interceptor As BatchRequestModificationInterceptHandler)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.RequestInterceptor : Microsoft.Azure.Batch.Protocol.BatchRequestModificationInterceptHandler -&gt; Microsoft.Azure.Batch.Protocol.RequestInterceptor" Usage="new Microsoft.Azure.Batch.Protocol.RequestInterceptor interceptor" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="interceptor" Type="Microsoft.Azure.Batch.Protocol.BatchRequestModificationInterceptHandler" />
      </Parameters>
      <Docs>
        <param name="interceptor"><span data-ttu-id="5146f-103">検査、変更、または、BatchRequest の無視を許可するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="5146f-103">A delegate that will be allowed to inspect, modify or ignore a BatchRequest.</span></span></param>
        <summary>
            <span data-ttu-id="5146f-104">指定された BatchRequestModificationInterceptHandler を呼び出す RequestInterceptor の新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5146f-104">Initializes a new instance of RequestInterceptor that calls a given BatchRequestModificationInterceptHandler.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModificationInterceptHandler">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.BatchRequestModificationInterceptHandler ModificationInterceptHandler { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.BatchRequestModificationInterceptHandler ModificationInterceptHandler" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.RequestInterceptor.ModificationInterceptHandler" />
      <MemberSignature Language="VB.NET" Value="Public Property ModificationInterceptHandler As BatchRequestModificationInterceptHandler" />
      <MemberSignature Language="F#" Value="member this.ModificationInterceptHandler : Microsoft.Azure.Batch.Protocol.BatchRequestModificationInterceptHandler with get, set" Usage="Microsoft.Azure.Batch.Protocol.RequestInterceptor.ModificationInterceptHandler" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.BatchRequestModificationInterceptHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5146f-105">取得または、BatchRequestModificationInterceptHandler を設定します。</span><span class="sxs-lookup"><span data-stu-id="5146f-105">Gets or sets the BatchRequestModificationInterceptHandler.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>