<Type Name="FabricTestCommandOperationIdAlreadyExistsException" FullName="System.Fabric.FabricTestCommandOperationIdAlreadyExistsException">
  <TypeSignature Language="C#" Value="public class FabricTestCommandOperationIdAlreadyExistsException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricTestCommandOperationIdAlreadyExistsException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricTestCommandOperationIdAlreadyExistsException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTestCommandOperationIdAlreadyExistsException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricTestCommandOperationIdAlreadyExistsException = class&#xA;    inherit FabricException" />
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
      <para>テスト コマンド既に存在する場合、つまり、重複する操作の識別子がある場合にスローされる例外。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTestCommandOperationIdAlreadyExistsException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricTestCommandOperationIdAlreadyExistsException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            新しいインスタンスを初期化<see cref="T:System.Fabric.FabricTestCommandOperationIdAlreadyExistsException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.TestCommandOperationIdAlreadyExists" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTestCommandOperationIdAlreadyExistsException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricTestCommandOperationIdAlreadyExistsException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricTestCommandOperationIdAlreadyExistsException : string -&gt; System.Fabric.FabricTestCommandOperationIdAlreadyExistsException" Usage="new System.Fabric.FabricTestCommandOperationIdAlreadyExistsException message" />
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
            新しいインスタンスを初期化<see cref="T:System.Fabric.FabricTestCommandOperationIdAlreadyExistsException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.TestCommandOperationIdAlreadyExists" />と指定したエラー メッセージ。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricTestCommandOperationIdAlreadyExistsException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricTestCommandOperationIdAlreadyExistsException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricTestCommandOperationIdAlreadyExistsException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricTestCommandOperationIdAlreadyExistsException" Usage="new System.Fabric.FabricTestCommandOperationIdAlreadyExistsException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">
          <para><see cref="T:System.Runtime.Serialization.SerializationInfo" />を含むオブジェクトがスローされた例外オブジェクト データをシリアル化します。</para>
        </param>
        <param name="context">
          <para>転送元または転送先に関するコンテキスト情報を格納する <see cref="T:System.Runtime.Serialization.StreamingContext" /> オブジェクト。 Context パラメーターは将来使用するために予約されており、null にすることができます。</para>
        </param>
        <summary>
            新しいインスタンスを初期化<see cref="T:System.Fabric.FabricTestCommandOperationIdAlreadyExistsException" />コンテキストを指定して、シリアル化されたオブジェクトのデータからのクラスです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTestCommandOperationIdAlreadyExistsException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricTestCommandOperationIdAlreadyExistsException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricTestCommandOperationIdAlreadyExistsException : string * Exception -&gt; System.Fabric.FabricTestCommandOperationIdAlreadyExistsException" Usage="new System.Fabric.FabricTestCommandOperationIdAlreadyExistsException (message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">
          <para>例外の原因を説明するエラー メッセージ。</para>
        </param>
        <param name="inner">
          <para>内部例外が指定されていない場合、現在の例外の原因となった例外。 <see cref="T:System.Exception" />クラスは、内部例外についての詳細を提供します。</para>
        </param>
        <summary>
            新しいインスタンスを初期化<see cref="T:System.Fabric.FabricTestCommandOperationIdAlreadyExistsException" />指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を持つクラス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>