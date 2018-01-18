<Type Name="StatelessServiceDescription" FullName="System.Fabric.Description.StatelessServiceDescription">
  <TypeSignature Language="C#" Value="public sealed class StatelessServiceDescription : System.Fabric.Description.ServiceDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatelessServiceDescription extends System.Fabric.Description.ServiceDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.StatelessServiceDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatelessServiceDescription&#xA;Inherits ServiceDescription" />
  <TypeSignature Language="F#" Value="type StatelessServiceDescription = class&#xA;    inherit ServiceDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.ServiceDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="489de-101">拡張<see cref="T:System.Fabric.Description.ServiceDescription" />ステートレスなサービスを作成するために必要な追加の情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="489de-101">Extends <see cref="T:System.Fabric.Description.ServiceDescription" /> to provide additional necessary information to create a stateless service.</span></span> </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatelessServiceDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatelessServiceDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="489de-102"><see cref="T:System.Fabric.Description.StatelessServiceDescription" /> クラスのインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="489de-102">Initializes an instance of the <see cref="T:System.Fabric.Description.StatelessServiceDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceCount">
      <MemberSignature Language="C#" Value="public int InstanceCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 InstanceCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatelessServiceDescription.InstanceCount" />
      <MemberSignature Language="VB.NET" Value="Public Property InstanceCount As Integer" />
      <MemberSignature Language="F#" Value="member this.InstanceCount : int with get, set" Usage="System.Fabric.Description.StatelessServiceDescription.InstanceCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="489de-103">取得またはこのサービス パーティションのインスタンスの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="489de-103">Gets or sets the instance count of this service partition.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="489de-104">このサービス パーティションのインスタンスの数。</span><span class="sxs-lookup"><span data-stu-id="489de-104">The instance count of this service partition.</span></span> </para>
        </value>
        <remarks>
          <para><span data-ttu-id="489de-105"><see cref="P:System.Fabric.Description.StatelessServiceDescription.InstanceCount" />プロパティは、このサービス用に作成するインスタンスの数を示します。</span><span class="sxs-lookup"><span data-stu-id="489de-105">The <see cref="P:System.Fabric.Description.StatelessServiceDescription.InstanceCount" /> property indicates the number of instances to be created for this service.</span></span> <span data-ttu-id="489de-106">指定されたインスタンス数は、Service Fabric によって維持されます。</span><span class="sxs-lookup"><span data-stu-id="489de-106">The specified number of instances will be maintained by Service Fabric.</span></span> <span data-ttu-id="489de-107">パーティションのステートレスなサービス<see cref="P:System.Fabric.Description.StatelessServiceDescription.InstanceCount" />パーティションごとに保持するインスタンスの数を示します。</span><span class="sxs-lookup"><span data-stu-id="489de-107">For a partitioned stateless service, <see cref="P:System.Fabric.Description.StatelessServiceDescription.InstanceCount" /> indicates the number of instances to be kept per partition.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>