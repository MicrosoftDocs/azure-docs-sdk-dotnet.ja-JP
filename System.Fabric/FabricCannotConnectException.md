<Type Name="FabricCannotConnectException" FullName="System.Fabric.FabricCannotConnectException">
  <TypeSignature Language="C#" Value="public sealed class FabricCannotConnectException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit FabricCannotConnectException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricCannotConnectException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricCannotConnectException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricCannotConnectException = class&#xA;    inherit FabricException" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.FabricException</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.MaintainabilityRules", "SA1402:FileMayOnlyContainASingleClass", Justification="Exception")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>この例外は、CannotConnect エラーがあることを示します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricCannotConnectException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricCannotConnectException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>
            新しいインスタンスを初期化<see cref="T:System.Fabric.FabricCannotConnectException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.FabricCannotConnect" />です。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricCannotConnectException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricCannotConnectException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricCannotConnectException : string -&gt; System.Fabric.FabricCannotConnectException" Usage="new System.Fabric.FabricCannotConnectException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">
          <para>例外の原因を説明するエラー メッセージ。</para>
        </param>
        <summary>
          <para>
            新しいインスタンスを初期化<see cref="T:System.Fabric.FabricCannotConnectException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.FabricCannotConnect" />と指定したエラー メッセージ。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricCannotConnectException (string message, Exception inner, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricCannotConnectException.#ctor(System.String,System.Exception,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricCannotConnectException : string * Exception * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricCannotConnectException" Usage="new System.Fabric.FabricCannotConnectException (message, inner, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="message">
          <para>例外の原因を説明するエラー メッセージ。</para>
        </param>
        <param name="inner">
          <para>内部例外が指定されていない場合、現在の例外の原因となった例外。 <see cref="T:System.Exception" />クラスは、内部例外についての詳細を提供します。</para>
        </param>
        <param name="errorCode">
          <para>例外に関連付けられているエラー コード。</para>
        </param>
        <summary>
            新しいインスタンスを初期化<see cref="T:System.Fabric.FabricCannotConnectException" />指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を持つクラス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>