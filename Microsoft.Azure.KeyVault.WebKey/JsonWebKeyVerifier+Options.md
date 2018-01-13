<Type Name="JsonWebKeyVerifier+Options" FullName="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier+Options">
  <TypeSignature Language="C#" Value="public enum JsonWebKeyVerifier.Options" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed JsonWebKeyVerifier/Options extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options" />
  <TypeSignature Language="VB.NET" Value="Public Enum JsonWebKeyVerifier.Options" />
  <TypeSignature Language="F#" Value="type JsonWebKeyVerifier.Options = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Flags</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DenyExtraneousFields">
      <MemberSignature Language="C#" Value="DenyExtraneousFields" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier/Options DenyExtraneousFields = int32(8)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.DenyExtraneousFields" />
      <MemberSignature Language="VB.NET" Value="DenyExtraneousFields" />
      <MemberSignature Language="F#" Value="DenyExtraneousFields = 8" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.DenyExtraneousFields" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier+Options</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6afcc-101">JsonWebKey オブジェクトは、対応するキーの種類によって使用されていないプロパティに値を表している場合は失敗します。</span><span class="sxs-lookup"><span data-stu-id="6afcc-101">Fails if the JsonWebKey object describes values at properties that are not used by the corresponding key type.</span></span>
            <span data-ttu-id="6afcc-102">防御いないプロパティに対して正しくセット、およびいくつかの形式の漏えいのも、これを使用します。</span><span class="sxs-lookup"><span data-stu-id="6afcc-102">Use this to defend against properties incorrectly set, and also some forms of leakage.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="DenyIncompatibleOperations">
      <MemberSignature Language="C#" Value="DenyIncompatibleOperations" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier/Options DenyIncompatibleOperations = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.DenyIncompatibleOperations" />
      <MemberSignature Language="VB.NET" Value="DenyIncompatibleOperations" />
      <MemberSignature Language="F#" Value="DenyIncompatibleOperations = 4" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.DenyIncompatibleOperations" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier+Options</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6afcc-103">失敗した場合があります、<code>"key_ops"</code>検証済みのキーの値には、互換性のない操作が含まれています。</span><span class="sxs-lookup"><span data-stu-id="6afcc-103">Fails if there the <code>"key_ops"</code> value of the verified key contains an incompatible operation.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="DenyPrivateKey">
      <MemberSignature Language="C#" Value="DenyPrivateKey" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier/Options DenyPrivateKey = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.DenyPrivateKey" />
      <MemberSignature Language="VB.NET" Value="DenyPrivateKey" />
      <MemberSignature Language="F#" Value="DenyPrivateKey = 1" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.DenyPrivateKey" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier+Options</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6afcc-104">すべての秘密キー マテリアルが存在する場合は失敗します。</span><span class="sxs-lookup"><span data-stu-id="6afcc-104">Fails if any private key material is present.</span></span> <span data-ttu-id="6afcc-105">漏えいを防ぐには、これを使用します。</span><span class="sxs-lookup"><span data-stu-id="6afcc-105">Use this to defend against leakage.</span></span> 
            </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier/Options None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier+Options</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6afcc-106">その他の指定しない場合は、この値を使用します。</span><span class="sxs-lookup"><span data-stu-id="6afcc-106">Use this value if you don't want to specify any other.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RequirePrivateKey">
      <MemberSignature Language="C#" Value="RequirePrivateKey" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier/Options RequirePrivateKey = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.RequirePrivateKey" />
      <MemberSignature Language="VB.NET" Value="RequirePrivateKey" />
      <MemberSignature Language="F#" Value="RequirePrivateKey = 2" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.RequirePrivateKey" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier+Options</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6afcc-107">秘密キー マテリアルが完全に存在しない場合は失敗します。</span><span class="sxs-lookup"><span data-stu-id="6afcc-107">Fails if private key material is not fully present.</span></span> <span data-ttu-id="6afcc-108">格納するか、秘密キーを保持する必要があるサブシステムに JsonWebKey 値をインポートする前に、これを使用します。</span><span class="sxs-lookup"><span data-stu-id="6afcc-108">Use this before storing or importing a JsonWebKey value into a subsystem that needs to keep the private key.</span></span> 
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ThrowException">
      <MemberSignature Language="C#" Value="ThrowException" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier/Options ThrowException = int32(1048576)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.ThrowException" />
      <MemberSignature Language="VB.NET" Value="ThrowException" />
      <MemberSignature Language="F#" Value="ThrowException = 1048576" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.ThrowException" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier+Options</ReturnType>
      </ReturnValue>
      <MemberValue>1048576</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6afcc-109">返さない<code>false</code>検証に失敗した; 代わりに例外をスローします。</span><span class="sxs-lookup"><span data-stu-id="6afcc-109">Do not return <code>false</code> if the verification fails; throws an exception instead.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="VerifyDecrypt">
      <MemberSignature Language="C#" Value="VerifyDecrypt" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier/Options VerifyDecrypt = int32(1024)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.VerifyDecrypt" />
      <MemberSignature Language="VB.NET" Value="VerifyDecrypt" />
      <MemberSignature Language="F#" Value="VerifyDecrypt = 1024" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.VerifyDecrypt" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier+Options</ReturnType>
      </ReturnValue>
      <MemberValue>1024</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6afcc-110">将来使用するために予約されています。</span><span class="sxs-lookup"><span data-stu-id="6afcc-110">Reserved for future use.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="VerifySign">
      <MemberSignature Language="C#" Value="VerifySign" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier/Options VerifySign = int32(2048)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.VerifySign" />
      <MemberSignature Language="VB.NET" Value="VerifySign" />
      <MemberSignature Language="F#" Value="VerifySign = 2048" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.VerifySign" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier+Options</ReturnType>
      </ReturnValue>
      <MemberValue>2048</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6afcc-111">将来使用するために予約されています。</span><span class="sxs-lookup"><span data-stu-id="6afcc-111">Reserved for future use.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>