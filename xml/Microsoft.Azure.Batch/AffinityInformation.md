<Type Name="AffinityInformation" FullName="Microsoft.Azure.Batch.AffinityInformation">
  <TypeSignature Language="C#" Value="public class AffinityInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AffinityInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.AffinityInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class AffinityInformation" />
  <TypeSignature Language="F#" Value="type AffinityInformation = class&#xA;    interface ITransportObjectProvider&lt;AffinityInformation&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4eb10-101">新しいタスクを開始するコンピューティング ノードを選択する、Batch service によって使用できる局所性のヒント。</span><span class="sxs-lookup"><span data-stu-id="4eb10-101">A locality hint that can be used by the Batch service to select a compute node on which to start a new task.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AffinityInformation (string affinityId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string affinityId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.AffinityInformation.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (affinityId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.AffinityInformation : string -&gt; Microsoft.Azure.Batch.AffinityInformation" Usage="new Microsoft.Azure.Batch.AffinityInformation affinityId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="affinityId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="affinityId"><span data-ttu-id="4eb10-102">以前に実行したタスクまたはコンピューティング ノードを表す不透明な文字列。</span><span class="sxs-lookup"><span data-stu-id="4eb10-102">An opaque string that represents a previously run task or compute node.</span></span></param>
        <summary>
            <span data-ttu-id="4eb10-103"><see cref="T:Microsoft.Azure.Batch.AffinityInformation" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4eb10-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.AffinityInformation" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AffinityId">
      <MemberSignature Language="C#" Value="public string AffinityId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AffinityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AffinityInformation.AffinityId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AffinityId As String" />
      <MemberSignature Language="F#" Value="member this.AffinityId : string" Usage="Microsoft.Azure.Batch.AffinityInformation.AffinityId" />
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
            <span data-ttu-id="4eb10-104">以前に実行したタスクまたはコンピューティング ノードを表す不透明な文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="4eb10-104">Gets an opaque string that represents a previously run task or compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>