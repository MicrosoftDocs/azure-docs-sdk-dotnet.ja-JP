<Type Name="StorageException" FullName="Microsoft.WindowsAzure.Storage.StorageException">
  <TypeSignature Language="C#" Value="public class StorageException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit StorageException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.StorageException" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type StorageException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Azure ストレージ サービスによってスローされる例外を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.StorageException : string -&gt; Microsoft.WindowsAzure.Storage.StorageException" Usage="new Microsoft.WindowsAzure.Storage.StorageException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">エラーを説明するメッセージ。</param>
        <summary>
            指定したエラー メッセージを使用して、<see cref="T:Microsoft.WindowsAzure.Storage.StorageException" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected StorageException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.StorageException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.WindowsAzure.Storage.StorageException" Usage="new Microsoft.WindowsAzure.Storage.StorageException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><see cref="T:System.Runtime.Serialization.SerializationInfo" />を保持するオブジェクトがスローされた例外オブジェクト データをシリアル化します。</param>
        <param name="context">転送元または転送先についてのコンテキスト情報を含む <see cref="T:System.Runtime.Serialization.StreamingContext" /> です。</param>
        <summary>
            シリアル化したデータを使用して、<see cref="T:Microsoft.WindowsAzure.Storage.StorageException" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>このコンストラクターは、ストリームを介して送信される例外オブジェクトを再構成する逆シリアル化中に呼び出されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.StorageException : string * Exception -&gt; Microsoft.WindowsAzure.Storage.StorageException" Usage="new Microsoft.WindowsAzure.Storage.StorageException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">例外のエラー メッセージ。</param>
        <param name="innerException">内部例外。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.StorageException" />指定したエラー メッセージと、この例外を生成した内部例外への参照を持つクラス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageException (Microsoft.WindowsAzure.Storage.RequestResult res, string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.RequestResult res, string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.#ctor(Microsoft.WindowsAzure.Storage.RequestResult,System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (res As RequestResult, message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.StorageException : Microsoft.WindowsAzure.Storage.RequestResult * string * Exception -&gt; Microsoft.WindowsAzure.Storage.StorageException" Usage="new Microsoft.WindowsAzure.Storage.StorageException (res, message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="res" Type="Microsoft.WindowsAzure.Storage.RequestResult" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="res">要求の結果。</param>
        <param name="message">例外メッセージ。</param>
        <param name="inner">内部例外。</param>
        <summary>
            指定されたパラメーターを使用して、<see cref="T:Microsoft.WindowsAzure.Storage.StorageException" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetObjectData">
      <MemberSignature Language="C#" Value="public override void GetObjectData (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void GetObjectData(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub GetObjectData (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="override this.GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit" Usage="storageException.GetObjectData (info, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">データを読み込む先の <see cref="T:System.Runtime.Serialization.SerializationInfo" /> オブジェクト。</param>
        <param name="context">このシリアル化の対象コンテキスト。</param>
        <summary>
            <see cref="T:System.Runtime.Serialization.SerializationInfo" /> オブジェクトに、対象オブジェクトをシリアル化するために必要なデータを設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestInformation">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RequestResult RequestInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.RequestResult RequestInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.StorageException.RequestInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestInformation As RequestResult" />
      <MemberSignature Language="F#" Value="member this.RequestInformation : Microsoft.WindowsAzure.Storage.RequestResult" Usage="Microsoft.WindowsAzure.Storage.StorageException.RequestInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RequestResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" />オブジェクトの<see cref="T:Microsoft.WindowsAzure.Storage.StorageException" />オブジェクト。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" />オブジェクトの<see cref="T:Microsoft.WindowsAzure.Storage.StorageException" />オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="storageException.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Microsoft Azure ストレージ クライアント ライブラリによってスローされる例外を表します。 
            </summary>
        <returns>例外を表す文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TranslateException">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.StorageException TranslateException (Exception ex, Microsoft.WindowsAzure.Storage.RequestResult reqResult);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.StorageException TranslateException(class System.Exception ex, class Microsoft.WindowsAzure.Storage.RequestResult reqResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.TranslateException(System.Exception,Microsoft.WindowsAzure.Storage.RequestResult)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TranslateException (ex As Exception, reqResult As RequestResult) As StorageException" />
      <MemberSignature Language="F#" Value="static member TranslateException : Exception * Microsoft.WindowsAzure.Storage.RequestResult -&gt; Microsoft.WindowsAzure.Storage.StorageException" Usage="Microsoft.WindowsAzure.Storage.StorageException.TranslateException (ex, reqResult)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageException</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ex" Type="System.Exception" />
        <Parameter Name="reqResult" Type="Microsoft.WindowsAzure.Storage.RequestResult" />
      </Parameters>
      <Docs>
        <param name="ex">変換する例外。</param>
        <param name="reqResult">要求の結果。</param>
        <summary>
            指定された例外を変換、<see cref="T:Microsoft.WindowsAzure.Storage.StorageException" />です。
            </summary>
        <returns>記憶域の例外。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TranslateException">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.StorageException TranslateException (Exception ex, Microsoft.WindowsAzure.Storage.RequestResult reqResult, Func&lt;System.IO.Stream,Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation&gt; parseError);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.StorageException TranslateException(class System.Exception ex, class Microsoft.WindowsAzure.Storage.RequestResult reqResult, class System.Func`2&lt;class System.IO.Stream, class Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation&gt; parseError) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.TranslateException(System.Exception,Microsoft.WindowsAzure.Storage.RequestResult,System.Func{System.IO.Stream,Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TranslateException (ex As Exception, reqResult As RequestResult, parseError As Func(Of Stream, StorageExtendedErrorInformation)) As StorageException" />
      <MemberSignature Language="F#" Value="static member TranslateException : Exception * Microsoft.WindowsAzure.Storage.RequestResult * Func&lt;System.IO.Stream, Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation&gt; -&gt; Microsoft.WindowsAzure.Storage.StorageException" Usage="Microsoft.WindowsAzure.Storage.StorageException.TranslateException (ex, reqResult, parseError)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageException</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ex" Type="System.Exception" />
        <Parameter Name="reqResult" Type="Microsoft.WindowsAzure.Storage.RequestResult" />
        <Parameter Name="parseError" Type="System.Func&lt;System.IO.Stream,Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation&gt;" />
      </Parameters>
      <Docs>
        <param name="ex">変換する例外。</param>
        <param name="reqResult">要求の結果。</param>
        <param name="parseError">拡張エラー情報を取得するエラーの解析に使用するデリゲート。</param>
        <summary>
            記憶域例外に指定された例外を変換します。
            </summary>
        <returns>記憶域の例外。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>