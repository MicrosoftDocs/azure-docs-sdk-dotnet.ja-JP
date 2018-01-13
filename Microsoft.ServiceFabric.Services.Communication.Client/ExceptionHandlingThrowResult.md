<Type Name="ExceptionHandlingThrowResult" FullName="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingThrowResult">
  <TypeSignature Language="C#" Value="public sealed class ExceptionHandlingThrowResult : Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ExceptionHandlingThrowResult extends Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingThrowResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ExceptionHandlingThrowResult&#xA;Inherits ExceptionHandlingResult" />
  <TypeSignature Language="F#" Value="type ExceptionHandlingThrowResult = class&#xA;    inherit ExceptionHandlingResult" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            クライアントからサービスへの要求を再試行できない場合、結果を処理する例外を示す
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionHandlingThrowResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingThrowResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionToThrow">
      <MemberSignature Language="C#" Value="public Exception ExceptionToThrow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception ExceptionToThrow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingThrowResult.ExceptionToThrow" />
      <MemberSignature Language="VB.NET" Value="Public Property ExceptionToThrow As Exception" />
      <MemberSignature Language="F#" Value="member this.ExceptionToThrow : Exception with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingThrowResult.ExceptionToThrow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この例外は、クライアントがスローされます。
            </summary>
        <value>例外をスローするには</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>