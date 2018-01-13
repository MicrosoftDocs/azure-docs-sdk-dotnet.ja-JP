<Type Name="TokenProvider" FullName="Microsoft.Azure.Relay.TokenProvider">
  <TypeSignature Language="C#" Value="public abstract class TokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TokenProvider extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.TokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TokenProvider" />
  <TypeSignature Language="F#" Value="type TokenProvider = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            追加のトークン プロバイダーを実装するのには、この抽象基本クラスを拡張できます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TokenProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.TokenProvider.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.Azure.Relay.TokenProvider" /> クラスの新しいインスタンスを初期化します。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Relay.TokenProvider CreateSharedAccessSignatureTokenProvider (string sharedAccessSignature);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Relay.TokenProvider CreateSharedAccessSignatureTokenProvider(string sharedAccessSignature) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (sharedAccessSignature As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string -&gt; Microsoft.Azure.Relay.TokenProvider" Usage="Microsoft.Azure.Relay.TokenProvider.CreateSharedAccessSignatureTokenProvider sharedAccessSignature" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Relay.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sharedAccessSignature" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sharedAccessSignature">共有アクセス署名</param>
        <summary>
            SharedAccessSignature に基づいて TokenProvider を構築します。
            </summary>
        <returns>共有アクセス署名を使用して初期化 TokenProvider</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Relay.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Relay.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (keyName As String, sharedAccessKey As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string -&gt; Microsoft.Azure.Relay.TokenProvider" Usage="Microsoft.Azure.Relay.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Relay.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyName">対応する SharedAccessKeyAuthorizationRule のキー名。</param>
        <param name="sharedAccessKey">SharedAccessKeyAuthorizationRule に関連付けられたキー</param>
        <summary>
            指定されたキー名と共有アクセス キーに基づく TokenProvider を構築します。
            </summary>
        <returns>指定された規則 Id とパスワードを使用して初期化 TokenProvider</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.SecurityToken&gt; GetTokenAsync (string audience, TimeSpan validFor);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.SecurityToken&gt; GetTokenAsync(string audience, valuetype System.TimeSpan validFor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.TokenProvider.GetTokenAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTokenAsync (audience As String, validFor As TimeSpan) As Task(Of SecurityToken)" />
      <MemberSignature Language="F#" Value="member this.GetTokenAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.SecurityToken&gt;" Usage="tokenProvider.GetTokenAsync (audience, validFor)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.SecurityToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="audience" Type="System.String" />
        <Parameter Name="validFor" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="audience">セキュリティ トークンの対象ユーザー。</param>
        <param name="validFor">どのくらいの期間、生成されたトークンはに対して有効にする必要があります。</param>
        <summary>
            取得、<see cref="T:Microsoft.Azure.Relay.SecurityToken" />指定された対象ユーザーと期間。
            </summary>
        <returns>新しく作成された SecurityToken を返すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnGetTokenAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.SecurityToken&gt; OnGetTokenAsync (string audience, TimeSpan validFor);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.SecurityToken&gt; OnGetTokenAsync(string audience, valuetype System.TimeSpan validFor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.TokenProvider.OnGetTokenAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnGetTokenAsync (audience As String, validFor As TimeSpan) As Task(Of SecurityToken)" />
      <MemberSignature Language="F#" Value="abstract member OnGetTokenAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.SecurityToken&gt;" Usage="tokenProvider.OnGetTokenAsync (audience, validFor)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.SecurityToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="audience" Type="System.String" />
        <Parameter Name="validFor" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="audience">セキュリティ トークンの対象ユーザー。</param>
        <param name="validFor">どのくらいの期間、生成されたトークンはに対して有効にする必要があります。</param>
        <summary>
            その SecurityTokens を生成する派生の TokenProvider 型によって実装されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThisLock">
      <MemberSignature Language="C#" Value="protected object ThisLock { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ThisLock" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.TokenProvider.ThisLock" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property ThisLock As Object" />
      <MemberSignature Language="F#" Value="member this.ThisLock : obj" Usage="Microsoft.Azure.Relay.TokenProvider.ThisLock" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            指定されたインスタンスの同期オブジェクトを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>