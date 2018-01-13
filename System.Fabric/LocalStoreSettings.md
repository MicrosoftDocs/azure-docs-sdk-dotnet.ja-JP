<Type Name="LocalStoreSettings" FullName="System.Fabric.LocalStoreSettings">
  <TypeSignature Language="C#" Value="public abstract class LocalStoreSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit LocalStoreSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.LocalStoreSettings" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class LocalStoreSettings" />
  <TypeSignature Language="F#" Value="type LocalStoreSettings = class" />
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
      <para>ローカル ストアのオプションの設定を表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected LocalStoreSettings (System.Fabric.LocalStoreKind storeKind);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.LocalStoreKind storeKind) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.LocalStoreSettings.#ctor(System.Fabric.LocalStoreKind)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (storeKind As LocalStoreKind)" />
      <MemberSignature Language="F#" Value="new System.Fabric.LocalStoreSettings : System.Fabric.LocalStoreKind -&gt; System.Fabric.LocalStoreSettings" Usage="new System.Fabric.LocalStoreSettings storeKind" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeKind" Type="System.Fabric.LocalStoreKind" />
      </Parameters>
      <Docs>
        <param name="storeKind">
          <para>A<see cref="T:System.Fabric.LocalStoreKind" />ストア プロバイダーの種類を表すオブジェクト。</para>
        </param>
        <summary>
          <para>指定されたストア プロバイダーの種類を持つクラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreKind">
      <MemberSignature Language="C#" Value="public System.Fabric.LocalStoreKind StoreKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.LocalStoreKind StoreKind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalStoreSettings.StoreKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoreKind As LocalStoreKind" />
      <MemberSignature Language="F#" Value="member this.StoreKind : System.Fabric.LocalStoreKind" Usage="System.Fabric.LocalStoreSettings.StoreKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.LocalStoreKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>ストア プロバイダーの種類を取得します。</para>
        </summary>
        <value>
          <para>ストア プロバイダーの種類として、<see cref="T:System.Fabric.LocalStoreKind" />オブジェクト。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>