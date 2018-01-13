<Type Name="FabricElementAlreadyExistsException" FullName="System.Fabric.FabricElementAlreadyExistsException">
  <TypeSignature Language="C#" Value="public class FabricElementAlreadyExistsException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricElementAlreadyExistsException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricElementAlreadyExistsException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricElementAlreadyExistsException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricElementAlreadyExistsException = class&#xA;    inherit FabricException" />
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
      <para>この例外は、競合しているエンティティが存在するための失敗を示します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricElementAlreadyExistsException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricElementAlreadyExistsException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>新しいインスタンスを初期化<see cref="T:System.Fabric.FabricElementAlreadyExistsException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.Unknown" />です。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricElementAlreadyExistsException (System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricElementAlreadyExistsException.#ctor(System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricElementAlreadyExistsException : System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricElementAlreadyExistsException" Usage="new System.Fabric.FabricElementAlreadyExistsException errorCode" />
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
          <para>新しいインスタンスを初期化<see cref="T:System.Fabric.FabricElementAlreadyExistsException" />クラスを指定したエラー コード。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricElementAlreadyExistsException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricElementAlreadyExistsException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricElementAlreadyExistsException : string -&gt; System.Fabric.FabricElementAlreadyExistsException" Usage="new System.Fabric.FabricElementAlreadyExistsException message" />
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
          <para>新しいインスタンスを初期化<see cref="T:System.Fabric.FabricElementAlreadyExistsException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.Unknown" />と指定したエラー メッセージ。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricElementAlreadyExistsException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricElementAlreadyExistsException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricElementAlreadyExistsException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricElementAlreadyExistsException" Usage="new System.Fabric.FabricElementAlreadyExistsException (info, context)" />
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
          <para>新しいインスタンスを初期化<see cref="T:System.Fabric.FabricElementAlreadyExistsException" />コンテキストを指定して、シリアル化されたオブジェクトのデータからのクラスです。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricElementAlreadyExistsException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricElementAlreadyExistsException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricElementAlreadyExistsException : string * Exception -&gt; System.Fabric.FabricElementAlreadyExistsException" Usage="new System.Fabric.FabricElementAlreadyExistsException (message, inner)" />
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
            新しいインスタンスを初期化<see cref="T:System.Fabric.FabricElementAlreadyExistsException" />指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を持つクラス。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricElementAlreadyExistsException (string message, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricElementAlreadyExistsException.#ctor(System.String,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricElementAlreadyExistsException : string * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricElementAlreadyExistsException" Usage="new System.Fabric.FabricElementAlreadyExistsException (message, errorCode)" />
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
          <para>新しいインスタンスを初期化<see cref="T:System.Fabric.FabricElementAlreadyExistsException" />クラスは、指定したエラー メッセージとエラー コード。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricElementAlreadyExistsException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricElementAlreadyExistsException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricElementAlreadyExistsException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricElementAlreadyExistsException" Usage="new System.Fabric.FabricElementAlreadyExistsException (info, context, errorCode)" />
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
          <para>新しいインスタンスを初期化<see cref="T:System.Fabric.FabricElementAlreadyExistsException" />クラスを指定したコンテキストとエラー コードの指定したエラー コード。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricElementAlreadyExistsException (string message, Exception inner, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricElementAlreadyExistsException.#ctor(System.String,System.Exception,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricElementAlreadyExistsException : string * Exception * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricElementAlreadyExistsException" Usage="new System.Fabric.FabricElementAlreadyExistsException (message, inner, errorCode)" />
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
            新しいインスタンスを初期化<see cref="T:System.Fabric.FabricElementAlreadyExistsException" />クラスを指定したエラー メッセージ、この例外と、指定されたエラー コードの原因となった内部例外への参照。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>