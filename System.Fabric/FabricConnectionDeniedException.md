<Type Name="FabricConnectionDeniedException" FullName="System.Fabric.FabricConnectionDeniedException">
  <TypeSignature Language="C#" Value="public class FabricConnectionDeniedException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricConnectionDeniedException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricConnectionDeniedException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricConnectionDeniedException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricConnectionDeniedException = class&#xA;    inherit FabricException" />
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
      <para>Service Fabric クラスターまたはサーバーが接続要求が拒否された場合にスローされる例外。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricConnectionDeniedException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricConnectionDeniedException.#ctor" />
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
            新しいインスタンスを初期化<see cref="T:System.Fabric.FabricConnectionDeniedException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.Unknown" />です。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricConnectionDeniedException (System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricConnectionDeniedException.#ctor(System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricConnectionDeniedException : System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricConnectionDeniedException" Usage="new System.Fabric.FabricConnectionDeniedException errorCode" />
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
          <para>
            新しいインスタンスを初期化<see cref="T:System.Fabric.FabricConnectionDeniedException" />クラスを指定したエラー コード。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricConnectionDeniedException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricConnectionDeniedException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricConnectionDeniedException : string -&gt; System.Fabric.FabricConnectionDeniedException" Usage="new System.Fabric.FabricConnectionDeniedException message" />
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
            新しいインスタンスを初期化<see cref="T:System.Fabric.FabricConnectionDeniedException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.Unknown" />と指定したエラー メッセージ。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricConnectionDeniedException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricConnectionDeniedException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricConnectionDeniedException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricConnectionDeniedException" Usage="new System.Fabric.FabricConnectionDeniedException (info, context)" />
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
          <para>
            新しいインスタンスを初期化<see cref="T:System.Fabric.FabricConnectionDeniedException" />コンテキストを指定して、シリアル化されたオブジェクトのデータからのクラスです。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricConnectionDeniedException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricConnectionDeniedException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricConnectionDeniedException : string * Exception -&gt; System.Fabric.FabricConnectionDeniedException" Usage="new System.Fabric.FabricConnectionDeniedException (message, inner)" />
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
            新しいインスタンスを初期化<see cref="T:System.Fabric.FabricConnectionDeniedException" />指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を持つクラス。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricConnectionDeniedException (string message, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricConnectionDeniedException.#ctor(System.String,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricConnectionDeniedException : string * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricConnectionDeniedException" Usage="new System.Fabric.FabricConnectionDeniedException (message, errorCode)" />
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
          <para>
            新しいインスタンスを初期化<see cref="T:System.Fabric.FabricConnectionDeniedException" />クラスは、指定したエラー メッセージとエラー コード。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricConnectionDeniedException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricConnectionDeniedException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricConnectionDeniedException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricConnectionDeniedException" Usage="new System.Fabric.FabricConnectionDeniedException (info, context, errorCode)" />
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
          <para>
            新しいインスタンスを初期化<see cref="T:System.Fabric.FabricConnectionDeniedException" />指定のコンテキストとエラー コードを含む、シリアル化されたオブジェクトのデータからのクラスです。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricConnectionDeniedException (string message, Exception inner, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricConnectionDeniedException.#ctor(System.String,System.Exception,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricConnectionDeniedException : string * Exception * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricConnectionDeniedException" Usage="new System.Fabric.FabricConnectionDeniedException (message, inner, errorCode)" />
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
            新しいインスタンスを初期化<see cref="T:System.Fabric.FabricConnectionDeniedException" />クラスを指定したエラー メッセージ、この例外と、指定されたエラー コードの原因となった内部例外への参照。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>