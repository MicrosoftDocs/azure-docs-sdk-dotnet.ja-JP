<Type Name="IWithData&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithData&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithData&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithData`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithData`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithData(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithData&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="068e9-101">アタッチした後に戻るに親アプリケーション ゲートウェイの段階です。</span><span class="sxs-lookup"><span data-stu-id="068e9-101">The stage of the parent application gateway to return to after attaching.</span></span></typeparam>
    <summary>
            <span data-ttu-id="068e9-102">SSL 証明書の内容を指定できるように、SSL 証明書の定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="068e9-102">The stage of an SSL certificate definition allowing to specify the contents of the SSL certificate.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPfxFromBytes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithPassword&lt;ParentT&gt; WithPfxFromBytes (params byte[] pfxData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithPassword`1&lt;!ParentT&gt; WithPfxFromBytes(unsigned int8[] pfxData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithData`1.WithPfxFromBytes(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPfxFromBytes (ParamArray pfxData As Byte()) As IWithPassword(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPfxFromBytes : byte[] -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithPassword&lt;'ParentT&gt;" Usage="iWithData.WithPfxFromBytes pfxData" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithPassword&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pfxData" Type="System.Byte[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="pfxData"><span data-ttu-id="068e9-103">PFX 形式で秘密キーの内容。</span><span class="sxs-lookup"><span data-stu-id="068e9-103">The contents of the private key in the PFX format.</span></span></param>
        <summary>
            <span data-ttu-id="068e9-104">Base64 でエンコードされたされません、PFX (PKCS #12) 形式で秘密キーの内容を指定します。</span><span class="sxs-lookup"><span data-stu-id="068e9-104">Specifies the contents of the private key in the PFX (PKCS#12) format, not base64-encoded.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="068e9-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="068e9-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPfxFromFile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithPassword&lt;ParentT&gt; WithPfxFromFile (System.IO.FileInfo pfxFile);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithPassword`1&lt;!ParentT&gt; WithPfxFromFile(class System.IO.FileInfo pfxFile) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithData`1.WithPfxFromFile(System.IO.FileInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPfxFromFile (pfxFile As FileInfo) As IWithPassword(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPfxFromFile : System.IO.FileInfo -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithPassword&lt;'ParentT&gt;" Usage="iWithData.WithPfxFromFile pfxFile" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithPassword&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pfxFile" Type="System.IO.FileInfo" />
      </Parameters>
      <Docs>
        <param name="pfxFile"><span data-ttu-id="068e9-106">PFX 形式のファイルです。</span><span class="sxs-lookup"><span data-stu-id="068e9-106">A file in the PFX format.</span></span></param>
        <summary>
            <span data-ttu-id="068e9-107">秘密キーの内容を取得する PFX (PKCS #12) ファイルを指定します。</span><span class="sxs-lookup"><span data-stu-id="068e9-107">Specifies the PFX (PKCS#12) file to get the private key content from.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="068e9-108">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="068e9-108">The next stage of the definition.</span></span></return>
        <throws><span data-ttu-id="068e9-109">Java.io.IOException により指定されたファイルに関する問題がある場合。</span><span class="sxs-lookup"><span data-stu-id="068e9-109">Java.io.IOException when there are problems with the provided file.</span></span></throws>
      </Docs>
    </Member>
  </Members>
</Type>