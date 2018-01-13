<Type Name="OperationData" FullName="System.Fabric.OperationData">
  <TypeSignature Language="C#" Value="public class OperationData : System.Collections.ObjectModel.Collection&lt;ArraySegment&lt;byte&gt;&gt;, System.Collections.Generic.IEnumerable&lt;ArraySegment&lt;byte&gt;&gt;, System.Fabric.IOperationData" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationData extends System.Collections.ObjectModel.Collection`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; implements class System.Collections.Generic.IEnumerable`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt;, class System.Collections.IEnumerable, class System.Fabric.IOperationData" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.OperationData" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationData&#xA;Inherits Collection(Of ArraySegment(Of Byte))&#xA;Implements IEnumerable(Of ArraySegment(Of Byte)), IOperationData" />
  <TypeSignature Language="F#" Value="type OperationData = class&#xA;    inherit Collection&lt;ArraySegment&lt;byte&gt;&gt;&#xA;    interface IOperationData&#xA;    interface seq&lt;ArraySegment&lt;byte&gt;&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Collections.ObjectModel.Collection&lt;System.ArraySegment&lt;System.Byte&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">System.ArraySegment&lt;System.Byte&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.ArraySegment&lt;System.Byte&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Fabric.IOperationData</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><see cref="T:System.Fabric.OperationData" />コピー状態の変更を転送し、レプリカの間でコンテキストをコピーするために使用します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationData ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.OperationData.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.OperationData" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationData (ArraySegment&lt;byte&gt; operationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.ArraySegment`1&lt;unsigned int8&gt; operationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.OperationData.#ctor(System.ArraySegment{System.Byte})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (operationData As ArraySegment(Of Byte))" />
      <MemberSignature Language="F#" Value="new System.Fabric.OperationData : ArraySegment&lt;byte&gt; -&gt; System.Fabric.OperationData" Usage="new System.Fabric.OperationData operationData" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="operationData" Type="System.ArraySegment&lt;System.Byte&gt;" />
      </Parameters>
      <Docs>
        <param name="operationData">
          <para><see cref="T:System.ArraySegment`1" />作成元のバイト数の<see cref="T:System.Fabric.OperationData" />オブジェクト。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.OperationData" />から、指定したクラス<see cref="T:System.ArraySegment`1" />バイトです。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationData (byte[] operationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] operationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.OperationData.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (operationData As Byte())" />
      <MemberSignature Language="F#" Value="new System.Fabric.OperationData : byte[] -&gt; System.Fabric.OperationData" Usage="new System.Fabric.OperationData operationData" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="operationData" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="operationData">
          <para>作成元のバイト配列、<see cref="T:System.Fabric.OperationData" />オブジェクト。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.OperationData" />クラス指定したバイト配列から。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationData (System.Collections.Generic.IEnumerable&lt;ArraySegment&lt;byte&gt;&gt; operationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; operationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.OperationData.#ctor(System.Collections.Generic.IEnumerable{System.ArraySegment{System.Byte}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (operationData As IEnumerable(Of ArraySegment(Of Byte)))" />
      <MemberSignature Language="F#" Value="new System.Fabric.OperationData : seq&lt;ArraySegment&lt;byte&gt;&gt; -&gt; System.Fabric.OperationData" Usage="new System.Fabric.OperationData operationData" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="operationData" Type="System.Collections.Generic.IEnumerable&lt;System.ArraySegment&lt;System.Byte&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="operationData">
          <para>作成元のバイト数、<see cref="T:System.Fabric.OperationData" />オブジェクト。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.OperationData" />クラスの指定したコレクションから<see cref="T:System.ArraySegment`1" />バイトです。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationData (System.Collections.Generic.IEnumerable&lt;byte[]&gt; operationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;unsigned int8[]&gt; operationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.OperationData.#ctor(System.Collections.Generic.IEnumerable{System.Byte[]})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (operationData As IEnumerable(Of Byte()))" />
      <MemberSignature Language="F#" Value="new System.Fabric.OperationData : seq&lt;byte[]&gt; -&gt; System.Fabric.OperationData" Usage="new System.Fabric.OperationData operationData" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="operationData" Type="System.Collections.Generic.IEnumerable&lt;System.Byte[]&gt;" />
      </Parameters>
      <Docs>
        <param name="operationData">
          <para><see cref="T:System.Collections.Generic.IEnumerable`1" />作成元のバイト配列の<see cref="T:System.Fabric.OperationData" />オブジェクト。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.OperationData" />バイト配列の指定したコレクションからのクラスです。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>