<Type Name="StatelessServiceTypeDescription" FullName="System.Fabric.Description.StatelessServiceTypeDescription">
  <TypeSignature Language="C#" Value="public sealed class StatelessServiceTypeDescription : System.Fabric.Description.ServiceTypeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatelessServiceTypeDescription extends System.Fabric.Description.ServiceTypeDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.StatelessServiceTypeDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatelessServiceTypeDescription&#xA;Inherits ServiceTypeDescription" />
  <TypeSignature Language="F#" Value="type StatelessServiceTypeDescription = class&#xA;    inherit ServiceTypeDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.ServiceTypeDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>ステートレス サービスの種類について説明します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatelessServiceTypeDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatelessServiceTypeDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>作成してのインスタンスを初期化、<see cref="T:System.Fabric.Description.StatelessServiceTypeDescription" />オブジェクト。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseImplicitHost">
      <MemberSignature Language="C#" Value="public bool UseImplicitHost { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseImplicitHost" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatelessServiceTypeDescription.UseImplicitHost" />
      <MemberSignature Language="VB.NET" Value="Public Property UseImplicitHost As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseImplicitHost : bool with get, set" Usage="System.Fabric.Description.StatelessServiceTypeDescription.UseImplicitHost" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービスが Service Fabric インターフェイスを実装しないことを指定します。 Service Fabric は、指定された実行可能ファイル (Exe) を開始する必要があります。</para>
        </summary>
        <value>
          <para><see cref="T:System.Boolean" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>