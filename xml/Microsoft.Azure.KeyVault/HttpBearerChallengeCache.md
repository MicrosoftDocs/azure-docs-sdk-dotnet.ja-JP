<Type Name="HttpBearerChallengeCache" FullName="Microsoft.Azure.KeyVault.HttpBearerChallengeCache">
  <TypeSignature Language="C#" Value="public sealed class HttpBearerChallengeCache" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HttpBearerChallengeCache extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.HttpBearerChallengeCache" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HttpBearerChallengeCache" />
  <TypeSignature Language="F#" Value="type HttpBearerChallengeCache = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a0112-101">Http ベアラー チャレンジのキャッシュを処理するためのシングルトン クラス</span><span class="sxs-lookup"><span data-stu-id="a0112-101">Singleton class for handling caching of the http bearer challenge</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.HttpBearerChallengeCache.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="member this.Clear : unit -&gt; unit" Usage="httpBearerChallengeCache.Clear " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a0112-102">キャッシュをクリアします。</span><span class="sxs-lookup"><span data-stu-id="a0112-102">Clears the cache</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetChallengeForURL">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.HttpBearerChallenge GetChallengeForURL (Uri url);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.KeyVault.HttpBearerChallenge GetChallengeForURL(class System.Uri url) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.HttpBearerChallengeCache.GetChallengeForURL(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetChallengeForURL (url As Uri) As HttpBearerChallenge" />
      <MemberSignature Language="F#" Value="member this.GetChallengeForURL : Uri -&gt; Microsoft.Azure.KeyVault.HttpBearerChallenge" Usage="httpBearerChallengeCache.GetChallengeForURL url" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.HttpBearerChallenge</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="url" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="url"> <span data-ttu-id="a0112-103">チャレンジがキャッシュされる URL です。</span><span class="sxs-lookup"><span data-stu-id="a0112-103">the URL that the challenge is cached for.</span></span></param>
        <summary>
            <span data-ttu-id="a0112-104">キャッシュされた URL のチャレンジを取得します。</span><span class="sxs-lookup"><span data-stu-id="a0112-104">Gets the challenge for the cached URL.</span></span>
            </summary>
        <returns><span data-ttu-id="a0112-105">キャッシュされたチャレンジまたは null それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="a0112-105">the cached challenge or null otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetInstance">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.KeyVault.HttpBearerChallengeCache GetInstance ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.KeyVault.HttpBearerChallengeCache GetInstance() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.HttpBearerChallengeCache.GetInstance" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetInstance () As HttpBearerChallengeCache" />
      <MemberSignature Language="F#" Value="static member GetInstance : unit -&gt; Microsoft.Azure.KeyVault.HttpBearerChallengeCache" Usage="Microsoft.Azure.KeyVault.HttpBearerChallengeCache.GetInstance " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.HttpBearerChallengeCache</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a0112-106">単一インスタンスを取得します。<see cref="T:Microsoft.Azure.KeyVault.HttpBearerChallengeCache" /></span><span class="sxs-lookup"><span data-stu-id="a0112-106">Gets the singleton instance of <see cref="T:Microsoft.Azure.KeyVault.HttpBearerChallengeCache" /></span></span></summary>
        <returns><span data-ttu-id="a0112-107">このクラスのインスタンス</span><span class="sxs-lookup"><span data-stu-id="a0112-107">Instance of this class</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveChallengeForURL">
      <MemberSignature Language="C#" Value="public void RemoveChallengeForURL (Uri url);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveChallengeForURL(class System.Uri url) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.HttpBearerChallengeCache.RemoveChallengeForURL(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveChallengeForURL (url As Uri)" />
      <MemberSignature Language="F#" Value="member this.RemoveChallengeForURL : Uri -&gt; unit" Usage="httpBearerChallengeCache.RemoveChallengeForURL url" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="url" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="url"> <span data-ttu-id="a0112-108">そのキャッシュされたチャレンジを削除する URL</span><span class="sxs-lookup"><span data-stu-id="a0112-108">the URL to remove its cached challenge</span></span> </param>
        <summary>
            <span data-ttu-id="a0112-109">指定された URL のキャッシュされたチャレンジを削除します。</span><span class="sxs-lookup"><span data-stu-id="a0112-109">Removes the cached challenge for the specified URL</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetChallengeForURL">
      <MemberSignature Language="C#" Value="public void SetChallengeForURL (Uri url, Microsoft.Azure.KeyVault.HttpBearerChallenge value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetChallengeForURL(class System.Uri url, class Microsoft.Azure.KeyVault.HttpBearerChallenge value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.HttpBearerChallengeCache.SetChallengeForURL(System.Uri,Microsoft.Azure.KeyVault.HttpBearerChallenge)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetChallengeForURL (url As Uri, value As HttpBearerChallenge)" />
      <MemberSignature Language="F#" Value="member this.SetChallengeForURL : Uri * Microsoft.Azure.KeyVault.HttpBearerChallenge -&gt; unit" Usage="httpBearerChallengeCache.SetChallengeForURL (url, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="url" Type="System.Uri" />
        <Parameter Name="value" Type="Microsoft.Azure.KeyVault.HttpBearerChallenge" />
      </Parameters>
      <Docs>
        <param name="url"> <span data-ttu-id="a0112-110">キャッシュ キーとしての課題に対応する URL</span><span class="sxs-lookup"><span data-stu-id="a0112-110">URL corresponding to challenge as cache key</span></span> </param>
        <param name="value"> <span data-ttu-id="a0112-111">チャレンジ</span><span class="sxs-lookup"><span data-stu-id="a0112-111">the challenge</span></span> </param>
        <summary>
            <span data-ttu-id="a0112-112">指定された URL のチャレンジをキャッシュします。</span><span class="sxs-lookup"><span data-stu-id="a0112-112">Caches the challenge for the specified URL</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>