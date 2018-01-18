<Type Name="PartitionSchemeDescription" FullName="System.Fabric.Description.PartitionSchemeDescription">
  <TypeSignature Language="C#" Value="public abstract class PartitionSchemeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit PartitionSchemeDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.PartitionSchemeDescription" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class PartitionSchemeDescription" />
  <TypeSignature Language="F#" Value="type PartitionSchemeDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Description.SingletonPartitionSchemeDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Description.UniformInt64RangePartitionSchemeDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Description.NamedPartitionSchemeDescription))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="93f20-101">サービスをパーティション分割する方法について説明します。</span><span class="sxs-lookup"><span data-stu-id="93f20-101">Describes how the service is partitioned.</span></span> <span data-ttu-id="93f20-102">これは、実際のパーティション分割スキームの説明の派生元である親エンティティです。</span><span class="sxs-lookup"><span data-stu-id="93f20-102">This is the parent entity from which the actual partitioning scheme descriptions are derived.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected PartitionSchemeDescription (System.Fabric.Description.PartitionScheme scheme);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Description.PartitionScheme scheme) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.PartitionSchemeDescription.#ctor(System.Fabric.Description.PartitionScheme)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (scheme As PartitionScheme)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.PartitionSchemeDescription : System.Fabric.Description.PartitionScheme -&gt; System.Fabric.Description.PartitionSchemeDescription" Usage="new System.Fabric.Description.PartitionSchemeDescription scheme" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="scheme" Type="System.Fabric.Description.PartitionScheme" />
      </Parameters>
      <Docs>
        <param name="scheme">
          <para>
            <span data-ttu-id="93f20-103"><see cref="T:System.Fabric.Description.PartitionScheme" />パーティション構成の種類を定義します。</span><span class="sxs-lookup"><span data-stu-id="93f20-103"><see cref="T:System.Fabric.Description.PartitionScheme" /> defines the kind of partition scheme.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="93f20-104">インスタンスを作成、<see cref="T:System.Fabric.Description.PartitionSchemeDescription" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="93f20-104">Instantiates a <see cref="T:System.Fabric.Description.PartitionSchemeDescription" /> class.</span></span> </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected PartitionSchemeDescription (System.Fabric.Description.PartitionSchemeDescription other);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Fabric.Description.PartitionSchemeDescription other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.PartitionSchemeDescription.#ctor(System.Fabric.Description.PartitionSchemeDescription)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (other As PartitionSchemeDescription)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.PartitionSchemeDescription : System.Fabric.Description.PartitionSchemeDescription -&gt; System.Fabric.Description.PartitionSchemeDescription" Usage="new System.Fabric.Description.PartitionSchemeDescription other" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.Description.PartitionSchemeDescription" />
      </Parameters>
      <Docs>
        <param name="other">
          <para><span data-ttu-id="93f20-105">パラメーターのコピー元となるパーティション スキームの説明。</span><span class="sxs-lookup"><span data-stu-id="93f20-105">The partition scheme description from which parameters are copied.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="93f20-106">インスタンスを作成、<see cref="T:System.Fabric.Description.PartitionSchemeDescription" />から別のパラメーターを持つクラス<see cref="T:System.Fabric.Description.PartitionSchemeDescription" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="93f20-106">Instantiates a <see cref="T:System.Fabric.Description.PartitionSchemeDescription" /> class with parameters from another <see cref="T:System.Fabric.Description.PartitionSchemeDescription" /> object.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.PartitionScheme Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.PartitionScheme Scheme" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PartitionSchemeDescription.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Scheme As PartitionScheme" />
      <MemberSignature Language="F#" Value="member this.Scheme : System.Fabric.Description.PartitionScheme" Usage="System.Fabric.Description.PartitionSchemeDescription.Scheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.PartitionScheme</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="93f20-107">サービスをパーティション分割する方法を指定します。</span><span class="sxs-lookup"><span data-stu-id="93f20-107">Specifies how the service is partitioned.</span></span> <span data-ttu-id="93f20-108">一般的な用途はプログラマに説明をキャストするためにできる<see cref="T:System.Fabric.Description.SingletonPartitionSchemeDescription" />、 <see cref="T:System.Fabric.Description.NamedPartitionSchemeDescription" />、または<see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" />です。</span><span class="sxs-lookup"><span data-stu-id="93f20-108">A common use is that it enables programmers to cast the description into <see cref="T:System.Fabric.Description.SingletonPartitionSchemeDescription" />, <see cref="T:System.Fabric.Description.NamedPartitionSchemeDescription" />, or <see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="93f20-109"><see cref="T:System.Fabric.Description.PartitionScheme" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="93f20-109">Returns <see cref="T:System.Fabric.Description.PartitionScheme" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>