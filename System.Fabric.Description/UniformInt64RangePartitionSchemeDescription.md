<Type Name="UniformInt64RangePartitionSchemeDescription" FullName="System.Fabric.Description.UniformInt64RangePartitionSchemeDescription">
  <TypeSignature Language="C#" Value="public sealed class UniformInt64RangePartitionSchemeDescription : System.Fabric.Description.PartitionSchemeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UniformInt64RangePartitionSchemeDescription extends System.Fabric.Description.PartitionSchemeDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UniformInt64RangePartitionSchemeDescription&#xA;Inherits PartitionSchemeDescription" />
  <TypeSignature Language="F#" Value="type UniformInt64RangePartitionSchemeDescription = class&#xA;    inherit PartitionSchemeDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.PartitionSchemeDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>整数の範囲が均等に複数のパーティションに割り当てられているパーティション構成について説明します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UniformInt64RangePartitionSchemeDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UniformInt64RangePartitionSchemeDescription (int partitionCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 partitionCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.#ctor(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionCount As Integer)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.UniformInt64RangePartitionSchemeDescription : int -&gt; System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" Usage="new System.Fabric.Description.UniformInt64RangePartitionSchemeDescription partitionCount" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="partitionCount">
          <para>スキーム内のパーティションの数。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" />パーティション数を指定することによってクラスです。</para>
        </summary>
        <remarks>範囲の低いキーが既定で長い。MinValue とキーの最高値を既定の長さ。MaxValue です。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UniformInt64RangePartitionSchemeDescription (int partitionCount, long lowKey, long highKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 partitionCount, int64 lowKey, int64 highKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.#ctor(System.Int32,System.Int64,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionCount As Integer, lowKey As Long, highKey As Long)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.UniformInt64RangePartitionSchemeDescription : int * int64 * int64 -&gt; System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" Usage="new System.Fabric.Description.UniformInt64RangePartitionSchemeDescription (partitionCount, lowKey, highKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionCount" Type="System.Int32" />
        <Parameter Name="lowKey" Type="System.Int64" />
        <Parameter Name="highKey" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="partitionCount">
          <para>スキーム内のパーティションの数。</para>
        </param>
        <param name="lowKey">範囲の低キー。</param>
        <param name="highKey">範囲の高キー。</param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" />クラス パーティション数と範囲の値を指定します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighKey">
      <MemberSignature Language="C#" Value="public long HighKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 HighKey" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.HighKey" />
      <MemberSignature Language="VB.NET" Value="Public Property HighKey As Long" />
      <MemberSignature Language="F#" Value="member this.HighKey : int64 with get, set" Usage="System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.HighKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはサービスでサポートされているキーの範囲の包含的上限を設定します。</para>
        </summary>
        <value>
          <para>サービスでサポートされているキーの範囲の包含的上限です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LowKey">
      <MemberSignature Language="C#" Value="public long LowKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LowKey" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.LowKey" />
      <MemberSignature Language="VB.NET" Value="Public Property LowKey As Long" />
      <MemberSignature Language="F#" Value="member this.LowKey : int64 with get, set" Usage="System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.LowKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはサービスでサポートされているキーの範囲の下限を設定します。</para>
        </summary>
        <value>
          <para>サービスでサポートされているキーの範囲の下限。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionCount">
      <MemberSignature Language="C#" Value="public int PartitionCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PartitionCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.PartitionCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PartitionCount : int with get, set" Usage="System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.PartitionCount" />
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
          <para>取得またはパーティションの数を設定します。</para>
        </summary>
        <value>
          <para>パーティションの数。</para>
        </value>
        <remarks>
          <para>これにこのサービスがパーティション分割されているパーティションの数を指定します。 各パーティションは、約数は同じキーを受け取ります。 減算することによって、番号が決まり<languagekeyword>HighKey</languagekeyword>から<languagekeyword>LowKey</languagekeyword>で合計で割ること<languagekeyword>PartitionCount</languagekeyword>です。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>