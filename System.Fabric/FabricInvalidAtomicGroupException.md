<Type Name="FabricInvalidAtomicGroupException" FullName="System.Fabric.FabricInvalidAtomicGroupException">
  <TypeSignature Language="C#" Value="public class FabricInvalidAtomicGroupException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricInvalidAtomicGroupException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricInvalidAtomicGroupException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricInvalidAtomicGroupException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricInvalidAtomicGroupException = class&#xA;    inherit FabricException" />
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
      <para>Service Fabric atomic グループが有効ではない場合にスローされる例外。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidAtomicGroupException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidAtomicGroupException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>新しいインスタンスを初期化<see cref="T:System.Fabric.FabricInvalidAtomicGroupException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.Unknown" />です。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidAtomicGroupException (System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidAtomicGroupException.#ctor(System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidAtomicGroupException : System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricInvalidAtomicGroupException" Usage="new System.Fabric.FabricInvalidAtomicGroupException errorCode" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="errorCode">
          <para>例外に関連付けられているエラー コード。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化<see cref="T:System.Fabric.FabricInvalidAtomicGroupException" />クラスを指定したエラー コード。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidAtomicGroupException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidAtomicGroupException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidAtomicGroupException : string -&gt; System.Fabric.FabricInvalidAtomicGroupException" Usage="new System.Fabric.FabricInvalidAtomicGroupException message" />
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
          <para>新しいインスタンスを初期化<see cref="T:System.Fabric.FabricInvalidAtomicGroupException" />指定したエラー メッセージを使用します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricInvalidAtomicGroupException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidAtomicGroupException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidAtomicGroupException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricInvalidAtomicGroupException" Usage="new System.Fabric.FabricInvalidAtomicGroupException (info, context)" />
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
          <para>新しいインスタンスを初期化<see cref="T:System.Fabric.FabricInvalidAtomicGroupException" />コンテキストを指定して、シリアル化されたオブジェクトのデータからのクラスです。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidAtomicGroupException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidAtomicGroupException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidAtomicGroupException : string * Exception -&gt; System.Fabric.FabricInvalidAtomicGroupException" Usage="new System.Fabric.FabricInvalidAtomicGroupException (message, inner)" />
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
          <para>
            新しいインスタンスを初期化<see cref="T:System.Fabric.FabricInvalidAtomicGroupException" />指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を持つクラス。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidAtomicGroupException (string message, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidAtomicGroupException.#ctor(System.String,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidAtomicGroupException : string * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricInvalidAtomicGroupException" Usage="new System.Fabric.FabricInvalidAtomicGroupException (message, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="message">
          <para>例外の原因を説明するエラー メッセージ。</para>
        </param>
        <param name="errorCode">
          <para>例外に関連付けられているエラー コード。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化<see cref="T:System.Fabric.FabricInvalidAtomicGroupException" />クラスを指定したメッセージとエラー コード。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricInvalidAtomicGroupException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidAtomicGroupException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidAtomicGroupException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricInvalidAtomicGroupException" Usage="new System.Fabric.FabricInvalidAtomicGroupException (info, context, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="info">
          <para><see cref="T:System.Runtime.Serialization.SerializationInfo" />を含むオブジェクトがスローされた例外オブジェクト データをシリアル化します。</para>
        </param>
        <param name="context">
          <para>転送元または転送先に関するコンテキスト情報を格納する <see cref="T:System.Runtime.Serialization.StreamingContext" /> オブジェクト。 Context パラメーターは将来使用するために予約されており、null にすることができます。</para>
        </param>
        <param name="errorCode">
          <para>例外に関連付けられているエラー コード。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化<see cref="T:System.Fabric.FabricInvalidAtomicGroupException" />指定のコンテキストとエラー コードを含む、シリアル化されたオブジェクトのデータからのクラスです。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidAtomicGroupException (string message, Exception inner, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidAtomicGroupException.#ctor(System.String,System.Exception,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidAtomicGroupException : string * Exception * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricInvalidAtomicGroupException" Usage="new System.Fabric.FabricInvalidAtomicGroupException (message, inner, errorCode)" />
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
          <para>
            新しいインスタンスを初期化<see cref="T:System.Fabric.FabricInvalidAtomicGroupException" />クラスを指定したエラー メッセージ、この例外と、指定されたエラー コードの原因となった内部例外への参照。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>