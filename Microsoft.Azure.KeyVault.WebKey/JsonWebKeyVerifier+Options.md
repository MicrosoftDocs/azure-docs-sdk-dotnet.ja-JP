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
            JsonWebKey オブジェクトは、対応するキーの種類によって使用されていないプロパティに値を表している場合は失敗します。
            防御いないプロパティに対して正しくセット、およびいくつかの形式の漏えいのも、これを使用します。
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
            失敗した場合があります、<code>"key_ops"</code>検証済みのキーの値には、互換性のない操作が含まれています。
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
            すべての秘密キー マテリアルが存在する場合は失敗します。 漏えいを防ぐには、これを使用します。 
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
            その他の指定しない場合は、この値を使用します。
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
            秘密キー マテリアルが完全に存在しない場合は失敗します。 格納するか、秘密キーを保持する必要があるサブシステムに JsonWebKey 値をインポートする前に、これを使用します。 
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
            返さない<code>false</code>検証に失敗した; 代わりに例外をスローします。
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
            将来使用するために予約されています。
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
            将来使用するために予約されています。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>