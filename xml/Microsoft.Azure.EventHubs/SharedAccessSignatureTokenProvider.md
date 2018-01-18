<Type Name="SharedAccessSignatureTokenProvider" FullName="Microsoft.Azure.EventHubs.SharedAccessSignatureTokenProvider">
  <TypeSignature Language="C#" Value="public class SharedAccessSignatureTokenProvider : Microsoft.Azure.EventHubs.TokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedAccessSignatureTokenProvider extends Microsoft.Azure.EventHubs.TokenProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.SharedAccessSignatureTokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedAccessSignatureTokenProvider&#xA;Inherits TokenProvider" />
  <TypeSignature Language="F#" Value="type SharedAccessSignatureTokenProvider = class&#xA;    inherit TokenProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.EventHubs.TokenProvider</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f9a25-101">共有を使用してトークンを生成する、SharedAccessSignatureTokenProvider アクセス キーまたは既存の署名。</span><span class="sxs-lookup"><span data-stu-id="f9a25-101">The SharedAccessSignatureTokenProvider generates tokens using a shared access key or existing signature.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected SharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, Func&lt;string,byte[]&gt; customKeyEncoder, TimeSpan tokenTimeToLive, Microsoft.Azure.EventHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string keyName, string sharedAccessKey, class System.Func`2&lt;string, unsigned int8[]&gt; customKeyEncoder, valuetype System.TimeSpan tokenTimeToLive, valuetype Microsoft.Azure.EventHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.SharedAccessSignatureTokenProvider.#ctor(System.String,System.String,System.Func{System.String,System.Byte[]},System.TimeSpan,Microsoft.Azure.EventHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.SharedAccessSignatureTokenProvider : string * string * Func&lt;string, byte[]&gt; * TimeSpan * Microsoft.Azure.EventHubs.TokenScope -&gt; Microsoft.Azure.EventHubs.SharedAccessSignatureTokenProvider" Usage="new Microsoft.Azure.EventHubs.SharedAccessSignatureTokenProvider (keyName, sharedAccessKey, customKeyEncoder, tokenTimeToLive, tokenScope)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="customKeyEncoder" Type="System.Func&lt;System.String,System.Byte[]&gt;" />
        <Parameter Name="tokenTimeToLive" Type="System.TimeSpan" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.EventHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="keyName"></param>
        <param name="sharedAccessKey"></param>
        <param name="customKeyEncoder"></param>
        <param name="tokenTimeToLive"></param>
        <param name="tokenScope"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildSignature">
      <MemberSignature Language="C#" Value="protected virtual string BuildSignature (string targetUri);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance string BuildSignature(string targetUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.SharedAccessSignatureTokenProvider.BuildSignature(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function BuildSignature (targetUri As String) As String" />
      <MemberSignature Language="F#" Value="abstract member BuildSignature : string -&gt; string&#xA;override this.BuildSignature : string -&gt; string" Usage="sharedAccessSignatureTokenProvider.BuildSignature targetUri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="targetUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="targetUri"></param>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EpochTime">
      <MemberSignature Language="C#" Value="public static readonly DateTime EpochTime;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.DateTime EpochTime" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.EventHubs.SharedAccessSignatureTokenProvider.EpochTime" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly EpochTime As DateTime " />
      <MemberSignature Language="F#" Value=" staticval mutable EpochTime : DateTime" Usage="Microsoft.Azure.EventHubs.SharedAccessSignatureTokenProvider.EpochTime" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9a25-102">00時 00分: 00 (utc) 木曜日 1、1970 年 1 月を表します。</span><span class="sxs-lookup"><span data-stu-id="f9a25-102">Represents 00:00:00 UTC Thursday 1, January 1970.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTokenAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.SecurityToken&gt; GetTokenAsync (string appliesTo, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.SecurityToken&gt; GetTokenAsync(string appliesTo, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.SharedAccessSignatureTokenProvider.GetTokenAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetTokenAsync (appliesTo As String, timeout As TimeSpan) As Task(Of SecurityToken)" />
      <MemberSignature Language="F#" Value="override this.GetTokenAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.SecurityToken&gt;" Usage="sharedAccessSignatureTokenProvider.GetTokenAsync (appliesTo, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.SecurityToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="appliesTo"><span data-ttu-id="f9a25-103">アクセス トークンが適用される URI</span><span class="sxs-lookup"><span data-stu-id="f9a25-103">The URI which the access token applies to</span></span></param>
        <param name="timeout"><span data-ttu-id="f9a25-104">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔</span><span class="sxs-lookup"><span data-stu-id="f9a25-104">The time span that specifies the timeout value for the message that gets the security token</span></span></param>
        <summary>
            <span data-ttu-id="f9a25-105">取得、<see cref="T:Microsoft.Azure.EventHubs.SecurityToken" />指定された対象ユーザーと期間。</span><span class="sxs-lookup"><span data-stu-id="f9a25-105">Gets a <see cref="T:Microsoft.Azure.EventHubs.SecurityToken" /> for the given audience and duration.</span></span>
            </summary>
        <returns>
          <see cref="T:Microsoft.Azure.EventHubs.SecurityToken" />
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>