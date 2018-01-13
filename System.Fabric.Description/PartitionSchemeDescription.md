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
      <para>サービスをパーティション分割する方法について説明します。 これは、実際のパーティション分割スキームの説明の派生元である親エンティティです。</para>
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
            <see cref="T:System.Fabric.Description.PartitionScheme" />パーティション構成の種類を定義します。</para>
        </param>
        <summary>
          <para>インスタンスを作成、<see cref="T:System.Fabric.Description.PartitionSchemeDescription" />クラスです。 </para>
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
          <para>パラメーターのコピー元となるパーティション スキームの説明。</para>
        </param>
        <summary>
          <para>
            インスタンスを作成、<see cref="T:System.Fabric.Description.PartitionSchemeDescription" />から別のパラメーターを持つクラス<see cref="T:System.Fabric.Description.PartitionSchemeDescription" />オブジェクト。
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
          <para>サービスをパーティション分割する方法を指定します。 一般的な用途はプログラマに説明をキャストするためにできる<see cref="T:System.Fabric.Description.SingletonPartitionSchemeDescription" />、 <see cref="T:System.Fabric.Description.NamedPartitionSchemeDescription" />、または<see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" />です。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Description.PartitionScheme" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>