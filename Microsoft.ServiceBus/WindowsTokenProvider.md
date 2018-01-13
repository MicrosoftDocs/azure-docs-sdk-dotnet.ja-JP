<Type Name="WindowsTokenProvider" FullName="Microsoft.ServiceBus.WindowsTokenProvider">
  <TypeSignature Language="C#" Value="public class WindowsTokenProvider : Microsoft.ServiceBus.TokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WindowsTokenProvider extends Microsoft.ServiceBus.TokenProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.WindowsTokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class WindowsTokenProvider&#xA;Inherits TokenProvider" />
  <TypeSignature Language="F#" Value="type WindowsTokenProvider = class&#xA;    inherit TokenProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.TokenProvider</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Service bus のトークン プロバイダーを表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BuildKey">
      <MemberSignature Language="C#" Value="protected override Microsoft.ServiceBus.TokenProvider.Key BuildKey (string appliesTo, string action);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Microsoft.ServiceBus.TokenProvider/Key BuildKey(string appliesTo, string action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WindowsTokenProvider.BuildKey(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function BuildKey (appliesTo As String, action As String) As TokenProvider.Key" />
      <MemberSignature Language="F#" Value="override this.BuildKey : string * string -&gt; Microsoft.ServiceBus.TokenProvider.Key" Usage="windowsTokenProvider.BuildKey (appliesTo, action)" />
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
        <returns>生成されたキー。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NormalizeAppliesTo">
      <MemberSignature Language="C#" Value="protected override string NormalizeAppliesTo (string appliesTo);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string NormalizeAppliesTo(string appliesTo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WindowsTokenProvider.NormalizeAppliesTo(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function NormalizeAppliesTo (appliesTo As String) As String" />
      <MemberSignature Language="F#" Value="override this.NormalizeAppliesTo : string -&gt; string" Usage="windowsTokenProvider.NormalizeAppliesTo appliesTo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appliesTo">正規化が適用される URI。</param>
        <summary>Normalize ターゲット アドレスの URI の形式を返します。</summary>
        <returns>正規化のターゲット アドレス URI 形式です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetToken">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginGetToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginGetToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WindowsTokenProvider.OnBeginGetToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginGetToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginGetToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="windowsTokenProvider.OnBeginGetToken (appliesTo, action, timeout, callback, state)" />
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
        <param name="appliesTo">トークンが適用されるオブジェクト。</param>
        <param name="action">アクション。</param>
        <param name="timeout">操作の期間です。</param>
        <param name="callback">引数 fir プロバイダー。</param>
        <param name="state">プロバイダーの状態。</param>
        <summary>プロバイダー サービスが開始されたときに、トークンを取得します。</summary>
        <returns>操作の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetWebToken">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginGetWebToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginGetWebToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WindowsTokenProvider.OnBeginGetWebToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginGetWebToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginGetWebToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="windowsTokenProvider.OnBeginGetWebToken (appliesTo, action, timeout, callback, state)" />
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
        <param name="appliesTo">トークンが適用されるオブジェクト。</param>
        <param name="action">アクション。</param>
        <param name="timeout">操作の期間です。</param>
        <param name="callback">引数 fir プロバイダー。</param>
        <param name="state">プロバイダーの状態。</param>
        <summary>プロバイダー サービスが開始されたときに、web トークンを取得します。</summary>
        <returns>操作の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetToken">
      <MemberSignature Language="C#" Value="protected override System.IdentityModel.Tokens.SecurityToken OnEndGetToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IdentityModel.Tokens.SecurityToken OnEndGetToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WindowsTokenProvider.OnEndGetToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndGetToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As SecurityToken" />
      <MemberSignature Language="F#" Value="override this.OnEndGetToken : IAsyncResult *  -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="windowsTokenProvider.OnEndGetToken (result, cacheUntil)" />
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
        <param name="result">操作の結果。</param>
        <param name="cacheUntil">データを格納するプロバイダーの時間の指定した期間です。</param>
        <summary>プロバイダー サービスが停止されたときに、トークンを取得します。</summary>
        <returns>取得したトークンです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetWebToken">
      <MemberSignature Language="C#" Value="protected override string OnEndGetWebToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string OnEndGetWebToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WindowsTokenProvider.OnEndGetWebToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndGetWebToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As String" />
      <MemberSignature Language="F#" Value="override this.OnEndGetWebToken : IAsyncResult *  -&gt; string" Usage="windowsTokenProvider.OnEndGetWebToken (result, cacheUntil)" />
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
        <param name="result">操作の結果。</param>
        <param name="cacheUntil">データを格納するプロバイダーの時間の指定した期間です。</param>
        <summary>プロバイダー サービスが停止されたときに、web トークンを取得します。</summary>
        <returns>取得された web トークンです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>