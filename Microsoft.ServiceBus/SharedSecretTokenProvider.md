<Type Name="SharedSecretTokenProvider" FullName="Microsoft.ServiceBus.SharedSecretTokenProvider">
  <TypeSignature Language="C#" Value="public class SharedSecretTokenProvider : Microsoft.ServiceBus.TokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedSecretTokenProvider extends Microsoft.ServiceBus.TokenProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.SharedSecretTokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedSecretTokenProvider&#xA;Inherits TokenProvider" />
  <TypeSignature Language="F#" Value="type SharedSecretTokenProvider = class&#xA;    inherit TokenProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.TokenProvider</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Web トークンのアサーションの名前/値ペアを返すし、非同期の共有シークレット トークン取得操作を実行するメソッドを提供します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BuildKey">
      <MemberSignature Language="C#" Value="protected override Microsoft.ServiceBus.TokenProvider.Key BuildKey (string appliesTo, string action);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Microsoft.ServiceBus.TokenProvider/Key BuildKey(string appliesTo, string action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SharedSecretTokenProvider.BuildKey(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function BuildKey (appliesTo As String, action As String) As TokenProvider.Key" />
      <MemberSignature Language="F#" Value="override this.BuildKey : string * string -&gt; Microsoft.ServiceBus.TokenProvider.Key" Usage="sharedSecretTokenProvider.BuildKey (appliesTo, action)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider+Key</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appliesTo">アクセス トークンが適用される URI。</param>
        <param name="action">要求された操作。</param>
        <summary>トークン プロバイダーをキーを生成します。</summary>
        <returns>トークン プロバイダー用に生成されたキー。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeSimpleWebTokenString">
      <MemberSignature Language="C#" Value="public static string ComputeSimpleWebTokenString (string issuerName, byte[] issuerSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string ComputeSimpleWebTokenString(string issuerName, unsigned int8[] issuerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SharedSecretTokenProvider.ComputeSimpleWebTokenString(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ComputeSimpleWebTokenString (issuerName As String, issuerSecret As Byte()) As String" />
      <MemberSignature Language="F#" Value="static member ComputeSimpleWebTokenString : string * byte[] -&gt; string" Usage="Microsoft.ServiceBus.SharedSecretTokenProvider.ComputeSimpleWebTokenString (issuerName, issuerSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="issuerName">発行者の名前。</param>
        <param name="issuerSecret">発行者のシークレット。</param>
        <summary>URL の文字列エンコードの指定した発行者名と発行者のシークレットを使用して、単純な web トークン アサーションの名前/値ペアを返します。</summary>
        <returns>URL は、単純な web トークン アサーションの名前/値ペアをエンコードします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeSimpleWebTokenString">
      <MemberSignature Language="C#" Value="public static string ComputeSimpleWebTokenString (string issuerName, string issuerSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string ComputeSimpleWebTokenString(string issuerName, string issuerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SharedSecretTokenProvider.ComputeSimpleWebTokenString(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ComputeSimpleWebTokenString (issuerName As String, issuerSecret As String) As String" />
      <MemberSignature Language="F#" Value="static member ComputeSimpleWebTokenString : string * string -&gt; string" Usage="Microsoft.ServiceBus.SharedSecretTokenProvider.ComputeSimpleWebTokenString (issuerName, issuerSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="issuerName">発行者の名前。</param>
        <param name="issuerSecret">発行者のシークレット。</param>
        <summary>URL の文字列エンコードの指定した発行者名と発行者のシークレットを使用して、単純な web トークン アサーションの名前/値ペアを返します。</summary>
        <returns>URL は、単純な web トークン アサーションの名前/値ペアをエンコードします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetToken">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginGetToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginGetToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SharedSecretTokenProvider.OnBeginGetToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginGetToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginGetToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="sharedSecretTokenProvider.OnBeginGetToken (appliesTo, action, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="appliesTo">アクセス トークンが適用される URI。</param>
        <param name="action">要求された操作。</param>
        <param name="timeout">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔。</param>
        <param name="callback">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</param>
        <summary>Begin get トークン アクションを実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />トークンを取得する非同期操作を参照するオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetWebToken">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginGetWebToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginGetWebToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SharedSecretTokenProvider.OnBeginGetWebToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginGetWebToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginGetWebToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="sharedSecretTokenProvider.OnBeginGetWebToken (appliesTo, action, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="appliesTo">アクセス トークンが適用される URI。</param>
        <param name="action">要求された操作。</param>
        <param name="timeout">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔。</param>
        <param name="callback">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</param>
        <summary>Begin get web トークンのアクションを実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" /> Web トークンを取得する非同期操作を参照するオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetToken">
      <MemberSignature Language="C#" Value="protected override System.IdentityModel.Tokens.SecurityToken OnEndGetToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IdentityModel.Tokens.SecurityToken OnEndGetToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SharedSecretTokenProvider.OnEndGetToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndGetToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As SecurityToken" />
      <MemberSignature Language="F#" Value="override this.OnEndGetToken : IAsyncResult *  -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="sharedSecretTokenProvider.OnEndGetToken (result, cacheUntil)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IdentityModel.Tokens.SecurityToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="cacheUntil" Type="System.DateTime&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />トークンを取得する非同期操作を参照するオブジェクト。</param>
        <param name="cacheUntil">このメソッドが戻るとき、有効期限の日付と時刻、キャッシュ内のトークンの情報が含まれています。</param>
        <summary>最後の get トークン アクションを実行します。</summary>
        <returns>セキュリティ トークン。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetWebToken">
      <MemberSignature Language="C#" Value="protected override string OnEndGetWebToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string OnEndGetWebToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SharedSecretTokenProvider.OnEndGetWebToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndGetWebToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As String" />
      <MemberSignature Language="F#" Value="override this.OnEndGetWebToken : IAsyncResult *  -&gt; string" Usage="sharedSecretTokenProvider.OnEndGetWebToken (result, cacheUntil)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="cacheUntil" Type="System.DateTime&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" /> Web トークンを取得する非同期操作を参照するオブジェクト。</param>
        <param name="cacheUntil">このメソッドが戻るとき、有効期限の日付と時刻、キャッシュ内のトークンの情報が含まれています。</param>
        <summary>End get web トークンのアクションを実行します。</summary>
        <returns>Web トークンです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>