<Type Name="KeyValueStoreTransactionSettings" FullName="System.Fabric.KeyValueStoreTransactionSettings">
  <TypeSignature Language="C#" Value="public class KeyValueStoreTransactionSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyValueStoreTransactionSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.KeyValueStoreTransactionSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyValueStoreTransactionSettings" />
  <TypeSignature Language="F#" Value="type KeyValueStoreTransactionSettings = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>サポートされているトランザクションの動作を記述する省略可能な設定を指定<see cref="T:System.Fabric.KeyValueStoreReplica" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreTransactionSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreTransactionSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>インスタンスを新規作成、<see cref="T:System.Fabric.KeyValueStoreTransactionSettings" />クラス..</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationBlockSize">
      <MemberSignature Language="C#" Value="public int SerializationBlockSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SerializationBlockSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreTransactionSettings.SerializationBlockSize" />
      <MemberSignature Language="VB.NET" Value="Public Property SerializationBlockSize As Integer" />
      <MemberSignature Language="F#" Value="member this.SerializationBlockSize : int with get, set" Usage="System.Fabric.KeyValueStoreTransactionSettings.SerializationBlockSize" />
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
          <para>レプリケーション操作にメモリを割り当てるときに使用するには、ブロック サイズ (バイト単位) を指定します。</para>
        </summary>
        <value>
          <para>ブロック サイズはバイト単位でレプリケーション操作にメモリを割り当てるときに使用されます。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>