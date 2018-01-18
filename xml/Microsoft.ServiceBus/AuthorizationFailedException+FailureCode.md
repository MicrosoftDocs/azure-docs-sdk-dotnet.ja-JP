<Type Name="AuthorizationFailedException+FailureCode" FullName="Microsoft.ServiceBus.AuthorizationFailedException+FailureCode">
  <TypeSignature Language="C#" Value="public enum AuthorizationFailedException.FailureCode" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed AuthorizationFailedException/FailureCode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.AuthorizationFailedException.FailureCode" />
  <TypeSignature Language="VB.NET" Value="Public Enum AuthorizationFailedException.FailureCode" />
  <TypeSignature Language="F#" Value="type AuthorizationFailedException.FailureCode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary><span data-ttu-id="ff577-101">認証の試行中にエラーの考えられる原因を列挙します。</span><span class="sxs-lookup"><span data-stu-id="ff577-101">Enumerates the possible causes of failure during authorization attempts.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ExpiredToken">
      <MemberSignature Language="C#" Value="ExpiredToken" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.AuthorizationFailedException/FailureCode ExpiredToken = int32(5)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.ExpiredToken" />
      <MemberSignature Language="VB.NET" Value="ExpiredToken" />
      <MemberSignature Language="F#" Value="ExpiredToken = 5" Usage="Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.ExpiredToken" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.AuthorizationFailedException+FailureCode</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary><span data-ttu-id="ff577-102">トークンの有効期限が切れたことを指定します。</span><span class="sxs-lookup"><span data-stu-id="ff577-102">Specifies that the token has expired.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Generic">
      <MemberSignature Language="C#" Value="Generic" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.AuthorizationFailedException/FailureCode Generic = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.Generic" />
      <MemberSignature Language="VB.NET" Value="Generic" />
      <MemberSignature Language="F#" Value="Generic = 0" Usage="Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.Generic" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.AuthorizationFailedException+FailureCode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary><span data-ttu-id="ff577-103">エラーは一般的なことを指定します。</span><span class="sxs-lookup"><span data-stu-id="ff577-103">Specifies that the error is generic.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="InvalidAudience">
      <MemberSignature Language="C#" Value="InvalidAudience" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.AuthorizationFailedException/FailureCode InvalidAudience = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.InvalidAudience" />
      <MemberSignature Language="VB.NET" Value="InvalidAudience" />
      <MemberSignature Language="F#" Value="InvalidAudience = 4" Usage="Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.InvalidAudience" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.AuthorizationFailedException+FailureCode</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary><span data-ttu-id="ff577-104">対象ユーザーが有効ではないことを指定します。</span><span class="sxs-lookup"><span data-stu-id="ff577-104">Specifies that the audience is invalid.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="InvalidClaim">
      <MemberSignature Language="C#" Value="InvalidClaim" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.AuthorizationFailedException/FailureCode InvalidClaim = int32(6)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.InvalidClaim" />
      <MemberSignature Language="VB.NET" Value="InvalidClaim" />
      <MemberSignature Language="F#" Value="InvalidClaim = 6" Usage="Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.InvalidClaim" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.AuthorizationFailedException+FailureCode</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary><span data-ttu-id="ff577-105">要求が有効ではないことを指定します。</span><span class="sxs-lookup"><span data-stu-id="ff577-105">Specifies that the claim is invalid.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="InvalidIssuer">
      <MemberSignature Language="C#" Value="InvalidIssuer" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.AuthorizationFailedException/FailureCode InvalidIssuer = int32(12)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.InvalidIssuer" />
      <MemberSignature Language="VB.NET" Value="InvalidIssuer" />
      <MemberSignature Language="F#" Value="InvalidIssuer = 12" Usage="Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.InvalidIssuer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.AuthorizationFailedException+FailureCode</ReturnType>
      </ReturnValue>
      <MemberValue>12</MemberValue>
      <Docs>
        <summary><span data-ttu-id="ff577-106">発行者が有効ではないことを指定します。</span><span class="sxs-lookup"><span data-stu-id="ff577-106">Specifies that the issuer is invalid.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="InvalidLifetime">
      <MemberSignature Language="C#" Value="InvalidLifetime" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.AuthorizationFailedException/FailureCode InvalidLifetime = int32(13)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.InvalidLifetime" />
      <MemberSignature Language="VB.NET" Value="InvalidLifetime" />
      <MemberSignature Language="F#" Value="InvalidLifetime = 13" Usage="Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.InvalidLifetime" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.AuthorizationFailedException+FailureCode</ReturnType>
      </ReturnValue>
      <MemberValue>13</MemberValue>
      <Docs>
        <summary><span data-ttu-id="ff577-107">有効期間が有効ではないことを指定します。</span><span class="sxs-lookup"><span data-stu-id="ff577-107">Specifies that the lifetime is invalid.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="InvalidSignature">
      <MemberSignature Language="C#" Value="InvalidSignature" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.AuthorizationFailedException/FailureCode InvalidSignature = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.InvalidSignature" />
      <MemberSignature Language="VB.NET" Value="InvalidSignature" />
      <MemberSignature Language="F#" Value="InvalidSignature = 3" Usage="Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.InvalidSignature" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.AuthorizationFailedException+FailureCode</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary><span data-ttu-id="ff577-108">署名が無効であるを指定します。</span><span class="sxs-lookup"><span data-stu-id="ff577-108">Specifies that the signature is invalid.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="MalformedToken">
      <MemberSignature Language="C#" Value="MalformedToken" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.AuthorizationFailedException/FailureCode MalformedToken = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.MalformedToken" />
      <MemberSignature Language="VB.NET" Value="MalformedToken" />
      <MemberSignature Language="F#" Value="MalformedToken = 2" Usage="Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.MalformedToken" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.AuthorizationFailedException+FailureCode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary><span data-ttu-id="ff577-109">トークンの形式が正しくないことを指定します。</span><span class="sxs-lookup"><span data-stu-id="ff577-109">Specifies that the token is malformed.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="MissingAudience">
      <MemberSignature Language="C#" Value="MissingAudience" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.AuthorizationFailedException/FailureCode MissingAudience = int32(7)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.MissingAudience" />
      <MemberSignature Language="VB.NET" Value="MissingAudience" />
      <MemberSignature Language="F#" Value="MissingAudience = 7" Usage="Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.MissingAudience" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.AuthorizationFailedException+FailureCode</ReturnType>
      </ReturnValue>
      <MemberValue>7</MemberValue>
      <Docs>
        <summary><span data-ttu-id="ff577-110">対象ユーザーが存在しないことを指定します。</span><span class="sxs-lookup"><span data-stu-id="ff577-110">Specifies that the audience is missing.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="MissingExpiresOn">
      <MemberSignature Language="C#" Value="MissingExpiresOn" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.AuthorizationFailedException/FailureCode MissingExpiresOn = int32(8)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.MissingExpiresOn" />
      <MemberSignature Language="VB.NET" Value="MissingExpiresOn" />
      <MemberSignature Language="F#" Value="MissingExpiresOn = 8" Usage="Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.MissingExpiresOn" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.AuthorizationFailedException+FailureCode</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary><span data-ttu-id="ff577-111">'上の有効期限の日付が不足していることを指定します。</span><span class="sxs-lookup"><span data-stu-id="ff577-111">Specifies that the 'expires on' date is missing.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="MissingIssuer">
      <MemberSignature Language="C#" Value="MissingIssuer" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.AuthorizationFailedException/FailureCode MissingIssuer = int32(9)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.MissingIssuer" />
      <MemberSignature Language="VB.NET" Value="MissingIssuer" />
      <MemberSignature Language="F#" Value="MissingIssuer = 9" Usage="Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.MissingIssuer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.AuthorizationFailedException+FailureCode</ReturnType>
      </ReturnValue>
      <MemberValue>9</MemberValue>
      <Docs>
        <summary><span data-ttu-id="ff577-112">発行者が不足していることを指定します。</span><span class="sxs-lookup"><span data-stu-id="ff577-112">Specifies that the issuer is missing.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="MissingSignature">
      <MemberSignature Language="C#" Value="MissingSignature" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.AuthorizationFailedException/FailureCode MissingSignature = int32(10)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.MissingSignature" />
      <MemberSignature Language="VB.NET" Value="MissingSignature" />
      <MemberSignature Language="F#" Value="MissingSignature = 10" Usage="Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.MissingSignature" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.AuthorizationFailedException+FailureCode</ReturnType>
      </ReturnValue>
      <MemberValue>10</MemberValue>
      <Docs>
        <summary><span data-ttu-id="ff577-113">署名が不足していることを指定します。</span><span class="sxs-lookup"><span data-stu-id="ff577-113">Specifies that the signature is missing.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="MissingToken">
      <MemberSignature Language="C#" Value="MissingToken" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.AuthorizationFailedException/FailureCode MissingToken = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.MissingToken" />
      <MemberSignature Language="VB.NET" Value="MissingToken" />
      <MemberSignature Language="F#" Value="MissingToken = 1" Usage="Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.MissingToken" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.AuthorizationFailedException+FailureCode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="ff577-114">トークンが不足していることを指定します。</span><span class="sxs-lookup"><span data-stu-id="ff577-114">Specifies that the token is missing.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="NotValidYet">
      <MemberSignature Language="C#" Value="NotValidYet" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.AuthorizationFailedException/FailureCode NotValidYet = int32(11)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.NotValidYet" />
      <MemberSignature Language="VB.NET" Value="NotValidYet" />
      <MemberSignature Language="F#" Value="NotValidYet = 11" Usage="Microsoft.ServiceBus.AuthorizationFailedException.FailureCode.NotValidYet" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.AuthorizationFailedException+FailureCode</ReturnType>
      </ReturnValue>
      <MemberValue>11</MemberValue>
      <Docs>
        <summary><span data-ttu-id="ff577-115">トークンがまだ正しくありませんを指定します。</span><span class="sxs-lookup"><span data-stu-id="ff577-115">Specifies that the token isn't valid yet.</span></span></summary>
      </Docs>
    </Member>
  </Members>
</Type>