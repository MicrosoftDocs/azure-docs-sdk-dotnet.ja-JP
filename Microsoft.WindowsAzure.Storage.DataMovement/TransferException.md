<Type Name="TransferException" FullName="Microsoft.WindowsAzure.Storage.DataMovement.TransferException">
  <TypeSignature Language="C#" Value="public class TransferException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit TransferException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type TransferException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Blob/FileTransferJobs によってスローされた例外の基本例外クラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferException (Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor(Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As TransferErrorCode)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException : Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferException" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException errorCode" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode" />
      </Parameters>
      <Docs>
        <param name="errorCode">エラー コードを転送します。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException : string -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferException" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">エラーを説明するメッセージ。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferException (Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode errorCode, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode errorCode, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor(Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As TransferErrorCode, message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException : Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode * string -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferException" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException (errorCode, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="errorCode">エラー コードを転送します。</param>
        <param name="message">例外メッセージ。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TransferException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferException" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">シリアル化情報。</param>
        <param name="context">ストリーミング コンテキスト。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferException (string message, Exception ex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception ex) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, ex As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException : string * Exception -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferException" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException (message, ex)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="ex" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">例外の原因を説明するエラー メッセージ。</param>
        <param name="ex">内部例外が指定されていない場合、現在の例外または null 参照の原因となった例外。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferException (Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode errorCode, string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode errorCode, string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor(Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode,System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As TransferErrorCode, message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException : Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode * string * Exception -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferException" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException (errorCode, message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="errorCode">エラー コードを転送します。</param>
        <param name="message">例外メッセージ。</param>
        <param name="innerException">内部例外。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As TransferErrorCode" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferException.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            詳細なエラー コードを取得します。
            </summary>
        <value>例外のエラー コード。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetObjectData">
      <MemberSignature Language="C#" Value="public override void GetObjectData (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void GetObjectData(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub GetObjectData (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="override this.GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit" Usage="transferException.GetObjectData (info, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">シリアル化情報オブジェクトです。</param>
        <param name="context">ストリーミング コンテキスト。</param>
        <summary>
            例外をシリアル化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>